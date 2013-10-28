##  Tools and frameworks: [inuit.css](http://inuitcss.com/)
Example:

    .pagination {
        text-align:center;
        letter-spacing:-0.31em;
        word-spacing:-0.43em;
    }
    [...]
    .pagination__first a:before {
        content:"\00AB" "\00A0";
    }
    .pagination__last a:after {
        content:"\00A0" "\00BB";
    }

<aside data-markdown class="notes">
    Harry Robert's (CSS Wizardry)
    Inuit is built on the BEM naming convention,
    but it's not a pure BEM framework.
</aside>
