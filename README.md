ansible-deployment-facts
========================

generate facts useful for deployments

usage:

    - action: deployment_facts

Now you have access to two variables inside your templates:

  - `deployment.build_path`: a temporary path on the host.
  - `deployment.timestamp`: a timestamp useful for the releases path