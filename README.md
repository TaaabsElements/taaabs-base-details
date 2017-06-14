# Taaabs-Base-Details

`<taaabs-base-details>` is a graphical element that displays the children of a base in a table.
It also allows to edit the table metadatas (label, comments).

In typical use, bind the `<taaabs-base-details>` to a base url.

        <taaabs-base-details  base-url="[[baseUrl]]" language="[[language]]">
        </taaabs-base-details>

or
        var elem = new TAAABS.BaseDetails("the_base_url");

----

## TODO

  - Better managing of the resources comments.
  - Better managing of Built-in Methods.
  - Load the base in case of not using central laoding.
  - Replace <iron-autogrow-textarea> with <paper-textarea>

For more information, see [the <taaabs-base-details> page](https://taaabselements.github.io/#/components/detail/taaabs-base-details)
