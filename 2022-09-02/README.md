Container queries

Container Query units

Pseudo classes
+ :has()
+ :is()
+ :where() // specificity = 0

Style queries

Dialog & Top layer

---

Container queries
https://www.oddbird.net/2022/08/18/cq-syntax/

Container query units:
https://www.oddbird.net/2022/08/18/cq-syntax/

Style queries:
https://blog.logrocket.com/new-css-style-queries

Pseudo classes:
https://blog.openreplay.com/modern-css-selectors

Dialog & Top layer:
https://developer.chrome.com/en/blog/what-is-the-top-layer/

---

```css

/* Use this to query another component state */

.global-header {
	container: global-header / inline-size;
	/* container-name: global-header; */
	/* container-type: inline-size | size; */
}

@container global-header style(background: ...) {
	.my-component {
		padding: 104px;
	}
}
```

```css
form:has(input:invalid) {
	border: red;
}
```

```css
ul:has(li:nth-child(9)) {
	display: flex;
	flex-direction: row;
	...
}
```