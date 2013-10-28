##  Preprocessors: LESS

    .block_name {
        &__element {
            color: #f00;
            &--modifier {
             font-weight: bold;
            }
        }
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
