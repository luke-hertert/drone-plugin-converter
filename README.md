# Usage

### Generate drone and harness plugin manifests on the local filesystem

```sh
./import-template-manifests

# or if you'd like to specify org and project names

./import-template-manifests my-project my-org

```

### Create step templates in Harness via API from local manifests.  You will be prompted for your Harness credentials.

```sh
accountId="KaZNXe69Qzm8KOo8bGCwwg"
project="Plugins"
org="default"

./create-harness-templates $accountId $project $org
```