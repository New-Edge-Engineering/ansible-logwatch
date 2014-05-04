## Ansibles - logwatch

Ansible role which installs and configures logwatch
([forked](https://github.com/Ansibles/logwatch)). Feedback, bug-reports, 
requests, is welcomed and can be done via
[github issues](https://github.com/New-Edge-Engineering/ansible-logwatch/issues).

#### Requirements & Dependencies
- Tested on Ansible 1.5.

#### Variables

```yaml
logwatch_email: "root@localhost"  # Email Address which Logwatch reports to
logwatch_detail: "low"            # The level of detail in the Logwatch report
logwatch_range: "yesterday"       # The default time range for the Logwatch report
logwatch_output: "stdout"         # The output method of the Logwatch report
logwatch_format: "text"           # The format of the Logwatch report
logwatch_cron_time: "daily"       # Cron special time specification nickname i.e. hourly, daily, weekly, month - must match with logwatch range!
```

#### License

Licensed under the MIT License. See the LICENSE file for details.

