# GSoC2021

Things [I](https://twitter.com/realDhruvPatel) did/learn as a part of Google summer Of Code in 2021 at Layer5.

## Organization: CNCF with Meshery

## MeshMap

Delivered a visual topology that subscribes to custom-written GraphQL resolvers and sources data from MeshSync, a Kubernetes custom controller using a NATS connection. The visual topology, in effect, takes the blinders off of service mesh operators, enabling them to see their infrastructure deployments as nodes represented in a three-dimensional canvas, and also allowing them to monitor and interact with specific part of their infrastructure using . This visualization works for any service mesh project and is the only visualizer of its kind… in the world.

![nsHei](https://user-images.githubusercontent.com/44001539/122640749-cb99a400-d11e-11eb-864a-a5a20be6deda.gif)

![logs](https://user-images.githubusercontent.com/44001539/125004483-3df30980-e077-11eb-964a-e83b7c02e51d.gif)

## GraphQL

1. Created a Standard tooling documentation in ruby to generates GraphQL docs for docs.meshery.io.

- https://github.com/meshery/meshery/pull/2989
- https://github.com/meshery/meshery/pull/2999

2. Worked on designing and implementing the Meshery API articture for Graphql.

- https://github.com/meshery/meshery/pull/3652
- https://github.com/meshery/meshery/pull/3181
- https://github.com/meshery/meshery/pull/3748
- https://github.com/meshery/meshery/pull/3753
- https://github.com/meshery/meshery/pull/3927
- https://github.com/meshery/meshery/pull/3775
- https://github.com/meshery/meshery/pull/3741

## Error Code Migration

Meshery created its [own framework](https://docs.meshery.io/reference/error-codes) (defined within MeshKit) to generate and document errors with unique identifiers, along with providing standard set of information to help describe and trobuleshoot the error. Help with migration of the error codes.

### Meshery

- https://github.com/meshery/meshery/pull/3505
- https://github.com/meshery/meshery/pull/3528
- https://github.com/meshery/meshery/pull/3263

### Meshery Adapters for Service Meshes

- https://github.com/meshery/meshery-kuma/pull/172
- https://github.com/meshery/meshery-kuma/pull/176
- https://github.com/meshery/meshery-osm/pull/98
- https://github.com/meshery/meshery-traefik-mesh/pull/97
- https://github.com/meshery/meshery-istio/pull/252

## SMI Conformance

Helped fix the `mesh vaildate` command to successfully run [SMI test](https://docs.meshery.io/functionality/service-mesh-interface) using mesheryctl.

- https://github.com/meshery/meshery/pull/3580
- https://github.com/meshery/meshery/pull/3689

## MeshSync

[MeshSync](https://docs.meshery.io/concepts/architecture/meshsync) is a custom Kubernetes controller developed by Layer5 to discover, listen and interact with the cluster resources. Fixed few minor issues as an effort to understand it.

- https://github.com/meshery/meshsync/pull/78
- https://github.com/meshery/meshsync/pull/82

## Other Contributions

UI Fixes:

- https://github.com/meshery/meshery/pull/3146
- https://github.com/meshery/meshery/pull/3299
- https://github.com/meshery/meshery/pull/3420
- https://github.com/meshery/meshery/pull/3763

Meshery Chart Fixes:

- https://github.com/meshery/meshery/pull/3220
- https://github.com/meshery/meshery/pull/3247
- https://github.com/meshery/meshery/pull/3263
- https://github.com/meshery/meshery/pull/3357
- https://github.com/meshery/meshery/pull/3220

Meshery Server Fixes:

- https://github.com/meshery/meshery/pull/3416
- https://github.com/meshery/meshery/pull/3742
- https://github.com/meshery/meshery/pull/3710

## Personal Take Aways

(As a future note to myself)

- Empower others to empower yourself.
- Promotion is just acknowledgement of what you are already doing.
- Have fun while you are at it.
