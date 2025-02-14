# workflow-testing
## TODO
Will probably drop k8s cluster a docker compose that gets run on an ec2.
Will still need tg/tf infra for this, but I can drop most of the setup for argo/k8s modules
Will need a workflow regardless to go into each app and build a container, upload to ghcr
EC2 will have to be provisioned to at least run docker compose

Need to separate sentences during transcription process based on inferences to get somewhat coherent results
* This is too intensive of a process to run during the transcription.
* The best looking approach is to chunk up the recordings from the collector bot so that each audio stream is collected as a separate file
* Have to test how long transcriptions are accurate for before they get cut off by mystery rate limit


## File Structure
```
.
├── .github
│   └── workflows
│       └── test.yaml
├── .gitignore
├── Hello-Files
├── LICENSE
└── README.md

3 directories, 5 files
```
