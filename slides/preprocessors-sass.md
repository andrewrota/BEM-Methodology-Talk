##  Preprocessors: SASS

    $b: ".block_name";

    #{$b}__element {
        color: #f00;
    }

    #{$b}__element--modifier {
        font-weight: bold;
    }

Produces

    .block_name__element {
        color: #f00;
    }
    .block_name__element--modifier {
        font-weight: bold;
    }

<aside data-markdown class="notes">

</aside>
