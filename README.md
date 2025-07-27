# golang-infra

Helm chart to deploy Golang Gin app.

## Structure

- Chart path: `charts/gin-app`
- To update image tag, modify: `values.yaml > image.tag`

## Example

```bash
helm upgrade --install gin-app ./charts/gin-app --namespace default
