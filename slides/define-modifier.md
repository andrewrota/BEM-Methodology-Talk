## Define Modifiers

    .nav-menu--item__simple {
      @extend .nav-menu;
      display: inline;
      float: none;
      & > a {
        line-height: 1;
        text-decoration: none;
      }
      &:after {
        content: " | ";
      }
      &:last-child:after {
        content: "";
      }
    }
