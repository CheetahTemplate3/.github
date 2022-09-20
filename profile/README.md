# CheetahTemplate3

## For users

Cheetah3 is a free and open source template engine for Python.
It currently supports Python 2.7 and 3.4+. License: MIT.

One can install a precompiled version from
[PyPI](https://pypi.org/project/Cheetah3/) using command

    pip install cheetah3

This is a small example:

    #from Cheetah.Template import Template
    #extends Template

    #set $people = [{'name' : 'Tom', 'mood' : 'Happy'}, {'name' : 'Dick',
                            'mood' : 'Sad'}, {'name' : 'Harry', 'mood' : 'Hairy'}]

    <strong>How are you feeling?</strong>
    <ul>
        #for $person in $people
            <li>
                $person['name'] is $person['mood']
            </li>
        #end for
    </ul>

The complete User Guide is published at https://cheetahtemplate.org/users_guide/

You can subscribe to
[cheetahtemplate-announce](https://sourceforge.net/projects/cheetahtemplate/lists/cheetahtemplate-announce)
mailing lists to receive announcements when a new release is being
rolled out.

[cheetahtemplate-discuss](https://sourceforge.net/projects/cheetahtemplate/lists/cheetahtemplate-discuss) mailing lists is for discussions.

StackOverflow: https://stackoverflow.com/questions/tagged/cheetah

## For developers and contributors

To help Cheetah3 please send
[pull requests](https://github.com/CheetahTemplate3/cheetah3/pulls).

Developer Guide is available at https://cheetahtemplate.org/dev_guide/
with some additional hints at https://cheetahtemplate.org/developers.html

Discussions should be conducted at cheetahtemplate-discuss mailing lists
(see above).
