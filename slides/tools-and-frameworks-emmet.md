##  Tools and frameworks: [Emmet](http://docs.emmet.io/filters/bem/)

Rather than writing

    ul.primary-navigation>li.primary-navigation__item*5

Instead write:

    ul.primary-navigation>li.-item*5|bem

Results in:

    <ul class="primary-navigation">
        <li class="primary-navigation__item"></li>
        <li class="primary-navigation__item"></li>
        <li class="primary-navigation__item"></li>
        <li class="primary-navigation__item"></li>
        <li class="primary-navigation__item"></li>
    </ul>


<aside data-markdown class="notes">

</aside>
