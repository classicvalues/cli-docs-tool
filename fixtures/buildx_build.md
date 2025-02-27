# docker buildx build

<!---MARKER_GEN_START-->
Start a build

### Aliases

`build`, `b`

### Options

| Name | Description |
| --- | --- |
| [`--add-host stringSlice`](https://docs.docker.com/engine/reference/commandline/build/#add-entries-to-container-hosts-file---add-host) | Add a custom host-to-IP mapping (format: `host:ip`) |
| `--allow stringSlice` | Allow extra privileged entitlement (e.g., `network.host`, `security.insecure`) |
| [`--build-arg stringArray`](https://docs.docker.com/engine/reference/commandline/build/#set-build-time-variables---build-arg) | Set build-time variables |
| `--builder string` | Override the configured builder instance |
| `--cache-from stringArray` | External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`) |
| `--cache-to stringArray` | Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`) |
| [`--cgroup-parent string`](https://docs.docker.com/engine/reference/commandline/build/#use-a-custom-parent-cgroup---cgroup-parent) | Optional parent cgroup for the container |
| [`-f`](https://docs.docker.com/engine/reference/commandline/build/#specify-a-dockerfile--f), [`--file string`](https://docs.docker.com/engine/reference/commandline/build/#specify-a-dockerfile--f) | Name of the Dockerfile (default: `PATH/Dockerfile`) |
| `--iidfile string` | Write the image ID to the file |
| `--label stringArray` | Set metadata for an image |
| `--load` | Shorthand for `--output=type=docker` |
| `--network string` | Set the networking mode for the `RUN` instructions during build |
| `-o`, `--output stringArray` | Output destination (format: `type=local,dest=path`) |
| `--platform stringArray` | Set target platform for build |
| `--push` | Shorthand for `--output=type=registry` |
| `-q`, `--quiet` | Suppress the build output and print image ID on success |
| `--secret stringArray` | Secret file to expose to the build (format: `id=mysecret,src=/local/secret`) |
| `--shm-size string` | Size of `/dev/shm` |
| `--ssh stringArray` | SSH agent socket or keys to expose to the build (format: `default\|<id>[=<socket>\|<key>[,<key>]]`) |
| [`-t`](https://docs.docker.com/engine/reference/commandline/build/#tag-an-image--t), [`--tag stringArray`](https://docs.docker.com/engine/reference/commandline/build/#tag-an-image--t) | Name and optionally a tag (format: `name:tag`) |
| [`--target string`](https://docs.docker.com/engine/reference/commandline/build/#specifying-target-build-stage---target) | Set the target build stage to build. |
| `--ulimit string` | Ulimit options |


<!---MARKER_GEN_END-->

