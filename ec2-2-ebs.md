## EC2 EBS

- Virtual hard disk drive in the cloud.

- Termination protection is turned off by default.

- On a EBS-backend instance, the default action is for the root EBS volume to be deleted when the instance is terminated.

- Default EBS root volumes and additional volumes can be encrypted.

- EBS Snapshots exists on S3

  - Are point in time copies of Volumes.
  - Are incremental.
  - Volumes that serve as root devices, you should stop the instance before taking the snapshot.
  - However you can take a snap while the instance is running.
  - You can create AMIs from both, volumes and snapshots.
  - Snapshots of encrypted volumes are encrypted automatically.
  - Volumes restored from encrypted snapshots are encrypted automatically.
  - You can share snapshots but only if they are encrypted.

- Possible change volume size on the fly, including changing the size and storage type.

- Volumes will always be in the same availability zone as the EC2 instance.

- Migrate/Move AZ, take a snapshot -> create AMI from snapshot -> launch AMI in the new AZ.

- Migrate/Move Region, take a snapshot -> create AMI from snapshot -> copy the AMI from one region to the other.

- Instance stores are Ephemeral are not EBS.

- By default ROOT volumes will be delete on termination. However with EBS volumes you can tell AWS to keep the root device volume.
