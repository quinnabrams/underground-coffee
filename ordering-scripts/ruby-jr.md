# Ruby Jr
A command line utility for automated ordering built with Node.js.

## How it works
ruby-jr has four commands:
 * `rjr status` or `rjr -s` prints an overview of information that
    ruby-jr knows about
    * the `-v` flag provides an overview of items that Ruby Jr thinks you need
    to order now.
 * `rjr update` or `rjr -u` pulls the latest inventory info from Airtable.
 * `rjr order` or `rjr -o` takes the items Ruby Jr thinks you need to order
    (which can be viewed with `rjr status -v` or `rjr -sv`) and adds them to
    your cart on Webstraunt Store.
