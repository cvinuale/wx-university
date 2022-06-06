CSS Responsive inner element:
.llb-responsive {
    margin-left: calc( (-100vw / 2) - 32px + (1436px / 2) );
    margin-right: calc( (-100vw / 2) - 32px + (1436px / 2) );
}

// Where 32px in the middle of the expression is the padding of the direct parent of the element


What forces layout / reflow?
https://gist.github.com/paulirish/5d52fb081b3570c81e3a

_index.html_ contains an example of forcing layout / reflow

Download Fiddler:
https://www.telerik.com/fiddler

Altnerative: HttpWatch
https://www.httpwatch.com/