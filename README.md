

## SDK development

Encore pins this package as a Git submodule. Clone the complete SDK with
`git clone --recurse-submodules --branch trunk https://github.com/encore-ecosystem/encore.git`
and edit this package under `packages/llvm/`. Sibling `path@` dependencies
are resolved from that checkout. Encore CI tests the exact package commits
with the compiler on all supported native targets. Published package archives
rewrite path dependencies to exact index versions.
