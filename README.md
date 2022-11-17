# template

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/chainguard-images/template/actions/workflows/release.yaml/badge.svg)](https://github.com/chainguard-images/template/actions/workflows/release.yaml)

WORK IN PROGRESS

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/template:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `latest` | `sha256:2837f2c69f77420ad92142ac9979fa2e4b41095cf72a7c4443950de523ff3dd3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:2837f2c69f77420ad92142ac9979fa2e4b41095cf72a7c4443950de523ff3dd3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


## Usage

WORK IN PROGRESS


## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/template:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/template:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/template"
      },
      "image": {
        "docker-manifest-digest": "sha256:2837f2c69f77420ad92142ac9979fa2e4b41095cf72a7c4443950de523ff3dd3"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "b7bd1f76328539265c0132229e23ce98aea0061f",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQDWHlD9k8O8dkjHMjfubOeW74+TbT9ZyuDItrTz9yDI1AIhAJXEH3kqATHjLgAZVO8RSaTniNWnMnakh6bVFNWt+Ppz",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI2NjVhYTY3MWYyOGZjOTkyY2JjYjQ0Y2I3ZGYzOWFlNzYxMzVkYWExZjgzODE4ZTFmMjcxZWZlY2MwNDFkNzUyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUURUR3hsVFEybVZqWTFDbGZQdEJlU3BOVDNvelcxZEI1QWlUWm9pQkVlNXJRSWhBTmx3TDRuSmRYQ0tKMHgvaW5iYkJJaTdTUzFZd0NiSnFveFpTOGVrbWFpRCIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwaFowRjNTVUpCWjBsVlZTdHdSbUpZWWtjMVFtbEZjekJUWjBJNFluaEdUMngyYmxjNGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlROTlJFbDNUV3BWZVZkb1kwNU5ha2w0VFZSRk0wMUVTWGhOYWxWNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZTTmtKaVYybERiazFJYWtoUFVGWTJOVk14T0djMlFYRndialJ0Y25oQlJFMXNNV1lLVUhBM1RuUkZiRWt2VEd3dlprUkpZMDlHU1RkclJIZHhjV3N6WnpRMWNreHdaR0ZEWlZCR1pVOUdlbVJXVkhocWIwdFBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlYxVEdKc0NubGlXamhIWmxFeVFYSnVlRzVGZFdObGNFNHdNalpOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdsT01rcHJUVmRaTTA1cVRYbFBSRlY2VDFSSk1rNVhUWGROVkUxNVRXcEpOVnBVU1hwWk1sVTFDazlIUm14WlZFRjNUbXBHYlUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEpUbFJJVDFWQlFVRlJSRUZGWjNkU1owbG9RVWxGWmk4emNXRUtaVmxuYTJzeVRHaEVPVVpUY1ZSd1REUkdjRXBLWlhOc2FsbHdVMWxDU0RWeFpsSlFRV2xGUVhBeVEwOUNNbE40U2tFeGJqVkthMkZOY0VaVk9XdHRkd3BRZFVKa2JWRkRlVTVNYTBWWFEzSlRUVEk0ZDBObldVbExiMXBKZW1vd1JVRjNUVVJoUVVGM1dsRkpkMk52UW1wMFducGpNRFZRTUZaRlpqUm5UMmhsQ2l0M2FtcGFjbHBrVm5GeGRXVkpUbWMxYVVkdFMyeFJWekJFWVc4elZETmlLM1ZSUlRrcmIwSlNWSEpGUVdwRlFUSXdTRmRrUTB4bmJFTlZjRE1yTlU0S1JreFpVR3hvUmtKWGRqQnhiVEUxTXpKQ1ZIbHFjak5zVG5oSFVXVmpMMmR3TkZkQ1R6VkJaSFIwVkVGR1kySlRDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668650598,
          "logIndex": 7243603,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "b7bd1f76328539265c0132229e23ce98aea0061f",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3484715304",
      "sha": "b7bd1f76328539265c0132229e23ce98aea0061f"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

