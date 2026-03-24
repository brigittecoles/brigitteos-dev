# brigitteos.dev

Atomic Capability Ontology namespace and documentation.

## What this serves

| URL | Content |
|-----|---------|
| `brigitteos.dev/ontology/capability/` | Human-readable ontology documentation |
| `brigitteos.dev/ontology/capability.jsonld` | JSON-LD full graph (616 nodes, 3526 edges) |
| `brigitteos.dev/ontology/capability.nt` | N-Triples RDF serialization |
| `brigitteos.dev/ontology/capability/context.jsonld` | Bare `@context` document |

## Namespace

```
PREFIX acl: <https://brigitteos.dev/ontology/capability#>
```

## Usage

```json
{
  "@context": "https://brigitteos.dev/ontology/capability/context.jsonld",
  "@type": "acl:Capability",
  "acl:hasAction": ["acl:action/architect"]
}
```

## Stats

- 20 capabilities across 6 clusters and 3 strategic zones
- 527 unique terms across 6 dimension types
- 60 curated atomic statements
- 600 dimension-capability edges

## Deployment

Hosted via GitHub Pages with custom domain `brigitteos.dev`.
