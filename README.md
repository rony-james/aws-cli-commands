# aws-cli-commands


## Sync objects
>> s3 sync updates any files that have a size or modified time that are different from files with the same name at the destination. The output displays specific operations performed during the sync. Notice that the operation recursively synchronizes the subdirectory MySubdirectory and its contents with s3://my-bucket/path/MySubdirectory

- aws s3 sync . s3://my-bucket/path
