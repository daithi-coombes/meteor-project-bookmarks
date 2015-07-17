# meteor-project-bookmarks
An interactive and reactive bookmarking user interface using the Meteor framework

### Goal
The goal is that users can place newsarticle, links to internal files and also
other media such as links to vidoes and pictures, on a system that links them
to a project or `bookmark folder`.

The user interface would be graphical, most probably using d3 and also reactive
using the meteor framework.

## Epic
User comes across some media that is relevant to a project, that they are either
a stakeholder in or not. They log into the system and are welcomed with a page
displaying all the bookmark folders in a nice interactive user interface.

They can then drag & drop the media to the relevant bookmark, or add the url to
the media.

Another user wants to know some information on a project. They login to the
system and click the project's folder on the welcome page. They are then shown
an interactive board with all the bookmarked items.

### Notes
These projects and bookmarks will probably have to be weighted somehow. As the
interactive nature of the user interface leads to some sort of `floating`
array of items, then the weighted measurement is need to bring the most vital
projects/items to the front. 
