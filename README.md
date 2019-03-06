# Developer utils

## `fij` - Find In Jar(s)

usage:

    fij searchstring jarfile [jarfile...]

This can be used to find class files in a jar or jars.
e.g.

    $ fij org.alfresco.web.scripts.SlingshotRemoteClient share/WEB-INF/lib/*.jar
    share/WEB-INF/lib/alfresco-share-4.1.1.jar

## `jsondiff` - Diff two json files

usage:

    jsondiff jsonfile1 jsonfile2

This command compares sorted and formatted versions of the two json files. Semantically identical files will show no differences.
