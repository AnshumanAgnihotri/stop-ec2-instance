# stop-ec2-instance
stop ec2 instance using github action.
write the workflow for manual event workflow_dispatch for stop the instance.
1. configure aws cli with github.(credential configure action@v1)
2. use this command and write the instane id.
      run: |
        INSTANCE_ID="your-instance-id-here"
        aws ec2 stop-instances --instance-ids $INSTANCE_ID
