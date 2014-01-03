ansible-deployment-facts
========================

generate facts useful for deployments

usage:

    roles:
      - { role: nicolai86.ansible-deployment-facts }

or if you've setup your roles dependencies properly:

    tasks:
      - action: deployment_facts

Now you have access to two variables inside your templates:

  - `deployment.build_path`: a temporary path on the host.
  - `deployment.timestamp`: a timestamp useful for the releases path