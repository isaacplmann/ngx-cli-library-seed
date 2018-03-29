# Ngx CLI Library Seed

Please replace this document with instructions on how to use Your Awesome Library.

`ngx-cli-library-seed` provides the following features:
1. Angular cli for building and running demo code
2. Angular cli for running tests
3. Demo app hosted on gh-pages
4. Lib code separate from demo code
5. Compiled code separate from source code
6. Publish to npm or pack into *.tgz for local testing

## Creating a new component in the library

To create a new component within the library folder, you'll have to specify the path of your library module. The ../lib/awesomelibrary points to ../lib/awesomelibrary.module.ts.

```ng generate component header --module ../lib/awesomelibrary```
