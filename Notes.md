Updating versions
-----------------

    # there will be references to old versions in docs.
    # update them.

      perl -p -i -e "s#styledown/v^[/]+/#styledown/v0.4.1/#g" Readme.md

    # release

      bump package.json
      vim History.md
      git release v0.4.0
      npm publish