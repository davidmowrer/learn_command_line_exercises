explain what the pushd and popd commands do, in your own words?

The pushd pushes along the file path and remembers Where you started.  For example:
pushd starts in the temp director pushd stuff/things/frank/joe, puts you in the
joe directory.  Now if you enter popd this will take you back to the temp diretory.
If you are in stuff and you enter pushd things/frank/joe, it takes you to the joe
directory.  If you do pushd alex/john it takes you to the John directory.  If you
do popd it takes you to the joe directory.  If you enter popd it takes you to the
stuff directory.

Explain the directories you visited:
I created five new directories for stuff: david, maggie, dava, karrie, jessica.
I did a pushd david/maggie/dava/karrie/jessica, this took me through the path to the
jessica directory.  popd took me back to the stuff directory.  Now I ran a pushd 
for each new directory entering a single directory until I reached the jessica
directory.  I ran popd five time to get back to the stuff directory.
