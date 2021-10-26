YAMLDIFF
========

This ~~is~~ _will be_ a diff-tool that can compare YAML-Documents.

Goals:
------

- [ ] can compare two files containing one YAML-document
- [ ] can compare two files containing multiple YAML-documents
- [ ] supports some flags of gnu diff
  - [ ] -q / quiet
  - [ ] -s / report only when files differ
- [ ] shows path to changed parts
- [ ] compares normalized representation
- [ ] single binary

Implementation Shortcuts:
-------------------------

- might only compare parsed datastructures
- multi-doc might only work for k8s-configs
- might be a big binary to bundle the whole runtime

License
-------

MIT, see LICENSE
