In the current Protege desktop 5.6.x there is a version conflict for the OWL API library:
- Protege core: 4.5.25
- `rdf-library`: 4.5.15

This has been reported at (https://github.com/protegeproject/rdf-library/issues/12 , but not being fixed yet.

In the meantime, I uploaded a fixed version of `rdf-library` plugin in the relases: 
You can simply donwload the JAR file and put it at
`$PROTEGE_HOME/plugins` and replace they existing `rdf-library` lib.

