# document

## installation

[installation](./installation.md)

## create connection

each input item description

- name: displayed in the dashboard. give yourself an easy-to-understand name.
- host: endpoint of database
- target
    - ec2: specify instance id (like i-0af01c0123456789a)
    - fargate: specify `ecs:${cluster_name}_${task_id}_${container_runtime_id}` (ref: https://github.com/aws/aws-cli/blob/c0edee0a7427b6e7b654df0696015e96105497a3/awscli/customizations/ecs/executecommand.py#L70)
