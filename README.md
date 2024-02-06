In the current Protege desktop 5.6.x there is a version conflict for the OWL API library:
- Protege core: 4.5.25
- `rdf-library`: 4.5.15

This has been reported at https://github.com/protegeproject/rdf-library/issues/12 , but not being fixed yet.

As a workaround, I published a fixed version of `rdf-library` plugin as an non-official release: https://github.com/LorenzBuehmann/rdf-library/releases/tag/rdf-library-3.0.0

Steps:
- download the JAR file which gives you `rdf-library-3.0.0-owlapi-fix.jar`
- remove `rdf-library-3.0.0.jar` from `$PROTEGE_HOME/plugins`
- move `rdf-library-3.0.0-owlapi-fix.jar` to `$PROTEGE_HOME/plugins`
- (or just rename the downloaded JAR before)
- in any case we just have to replace the old `rdf-library` JAR file

