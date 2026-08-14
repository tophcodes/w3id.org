# /aleph/

Namespace for [Aleph Garden](https://github.com/aleph-garden), whose published
RDF vocabularies live in [aleph-garden/vocab](https://github.com/aleph-garden/vocab).

Vocabularies are minted under `/ns/<name>`, their SHACL shapes under
`/ns/<name>/shapes`, and terms in the hash namespace of the document each
resolves to — so `https://w3id.org/aleph/ns/food#substance` is a term of the
food vocabulary. Two rewrite rules cover every vocabulary, present and future;
the list of what exists belongs in the vocabulary repository rather than here.

These are working drafts, so redirects are `302`. A redirect becomes `303` with
content negotiation once its vocabulary is declared stable.

## Maintainer

Christopher Mühl
toki@toph.so
GitHub: [@tophcodes](https://github.com/tophcodes)
