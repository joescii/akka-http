# mapRouteResult

## Description

Changes the message the inner route sends to the responder.

The `mapRouteResult` directive is used as a building block for @ref[Custom Directives](../custom-directives.md) to transform the
`RouteResult` coming back from the inner route.

See @ref[Result Transformation Directives](index.md#result-transformation-directives-java) for similar directives.

## Example

@@snip [BasicDirectivesExamplesTest.java]($test$/java/docs/http/javadsl/server/directives/BasicDirectivesExamplesTest.java) { #mapRouteResult }