**Note**: This public repo contains the documentation for the private GitHub repo <https://github.com/gruntwork-io/module-aws-monitoring>.
We publish the documentation publicly so it turns up in online searches, but to see the source code, you must be a Gruntwork customer.
If you're already a Gruntwork customer, the original source for this file is at: <https://github.com/gruntwork-io/module-aws-monitoring/blob/master/modules/alarms/README.md>.
If you're not a customer, contact us at <info@gruntwork.io> or <http://www.gruntwork.io> for info on how to get access!

# Alarm modules

This folder contains modules that configure [CloudWatch
Alarms](http://docs.aws.amazon.com/AmazonCloudWatch/latest/DeveloperGuide/AlarmThatSendsEmail.html) to go off and
email or SMS you when something is going wrong. The modules are:

* [asg-cpu-alarms](./asg-cpu-alarms): An alarm that goes off if CPU usage in an Auto Scaling Group (ASG) is too high.
* [asg-disk-alarms](./asg-disk-alarms): An alarm that goes off if disk usage in an Auto Scaling Group (ASG) is too high.
* [asg-memory-alarms](./asg-memory-alarms): An alarm that goes off if memory usage in an Auto Scaling Group (ASG) is
  too high.
* [ec2-cpu-alarms](./ec2-cpu-alarms): An alarm that goes off if CPU usage for an EC2 instance is too high.
* [ec2-disk-alarms](./ec2-disk-alarms): An alarm that goes off if disk usage for an EC2 instance is too high.
* [ec2-memory-alarms](./ec2-memory-alarms): An alarm that goes off if memory usage for an EC2 instance is too high.
* [ecs-cluster-alamrs](./ecs-cluster-alarms): Alarms for an ECS cluster that go off if CPU or memory usage is too high
  across the cluster.
* [ecs-service-alamrs](./ecs-cluster-alarms): Alarms for an ECS service that go off if CPU or memory usage is too high
  for this service.
* [elb-alarms](./elb-alarms): A set of ELB alarms that go off if the latency gets too high, or there are
  too many 5xx errors, or too few requests are coming in.
* [rds-alarms](./rds-alarms): A set of RDS alarms that go off if the CPU usage, number of connections, or latency gets
  too high or if the available memory or disk space gets too low.
* [route53-health-check-alarms](./route53-health-check-alarms): Monitor a given domain (e.g. example.com) using Route
  53 and trigger an alarm if that domain is down or unresponsive.
* [scheduled-job-alarm](./scheduled-job-alarm): An alarm that goes off if a scheduled job (e.g. a cron job) fails to
  run.

Click on each module above to see its documentation. Head over to the [examples folder](/examples) for examples.

