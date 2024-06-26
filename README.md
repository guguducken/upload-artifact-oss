# Upload Artifact to OSS

## Inputs
~~~yaml
inputs:
    access_key:
        description: access key used to access oss service
        required: true
    artifact_path:
        description: The path used to obtain the artifact
        required: true
    bucket:
        description: the bucket used to store uploaded artifacts in oss
        required: true
    oss_path:
        description: The path where the artifact is stored in the bucket
        required: true
    provider:
        description: oss provider used to upload and store artifacts, currently supports cos
        required: true
        default: cos
    region:
        description: the region where the oss service is located
        required: true
    retry_times:
        description: The number of retries that can be made when uploading artifacts，default is 1
        required: false
        default: "1"
    secret_key:
        description: secret key used to access oss service
        required: true
    storage_class:
        description: The storage type when the artifact is stored in the bucket
        required: true
~~~

## Outputs
~~~yaml
~~~