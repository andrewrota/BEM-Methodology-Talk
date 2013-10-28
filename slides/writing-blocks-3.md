##  Writing Blocks

    .nav-menu {
      display: block;
      margin: 0;
      padding: 0;
      width: 100%;
      float: right;
    }

    .nav-menu--items {
      margin: 0;
      padding: 0;
    }

    .nav-menu--item {
      float: left;
      list-style-type: none;
      margin-left: 0.5%;
      text-align: center;
      width: 12%;
      & > a {
        background: $primaryColor;
        color: white;
        display: block;
        font-size: .9em;
        line-height: 3.2;
        text-decoration: none;
        &:hover {
          background: $primaryColorLighter;
          -webkit-transform: rotate(10deg);
          transform: rotate(10deg);
          -webkit-transition: all .25s linear;
          -moz-transition: all .25s linear;
          -o-transition: all .25s linear;
          transition: all .25s linear;
        }
      }
    }

<aside data-markdown class="notes">

</aside>
