
💰 Infracost estimate: **monthly cost will increase by $586 (+73%) 📈**
<table>
  <thead>
    <td>Project</td>
    <td>Previous</td>
    <td>New</td>
    <td>Diff</td>
  </thead>
  <tbody>
    <tr>
      <td>infracost/infracost-azure-devop...les/terraform-project/code/dev</td>
      <td align="right">$52</td>
      <td align="right">$77</td>
      <td>+$25 (+49%)</td>
    </tr>
    <tr>
      <td>infracost/infracost-azure-devop...es/terraform-project/code/prod</td>
      <td align="right">$748</td>
      <td align="right">$1,308</td>
      <td>+$561 (+75%)</td>
    </tr>
    <tr>
      <td>All projects</td>
      <td align="right">$800</td>
      <td align="right">$1,386</td>
      <td>+$586 (+73%)</td>
    </tr>
  </tbody>
</table>


<details>
<summary><strong>Infracost output</strong></summary>

```
Project: infracost/infracost-azure-devops/examples/terraform-project/code/dev
Module path: dev

~ module.base.aws_instance.web_app
  +$25 ($52 → $77)

    ~ Instance usage (Linux/UNIX, on-demand, t2.micro → t2.medium)
      +$25 ($8 → $34)

Monthly cost change for infracost/infracost-azure-devops/examples/terraform-project/code/dev (Module path: dev)
Amount:  +$25 ($52 → $77)
Percent: +49%

──────────────────────────────────
Project: infracost/infracost-azure-devops/examples/terraform-project/code/prod
Module path: prod

~ module.base.aws_instance.web_app
  +$561 ($748 → $1,308)

    ~ Instance usage (Linux/UNIX, on-demand, m5.4xlarge → m5.8xlarge)
      +$561 ($561 → $1,121)

Monthly cost change for infracost/infracost-azure-devops/examples/terraform-project/code/prod (Module path: prod)
Amount:  +$561 ($748 → $1,308)
Percent: +75%

──────────────────────────────────
Key: ~ changed, + added, - removed

4 cloud resources were detected:
∙ 4 were estimated, all of which include usage-based costs, see https://infracost.io/usage-file
```
</details>

This comment will be updated when the cost estimate changes.

<sub>
  Is this comment useful? <a href="https://dashboard.infracost.io/feedback/redirect?runId=&value=yes" rel="noopener noreferrer" target="_blank">Yes</a>, <a href="https://dashboard.infracost.io/feedback/redirect?runId=&value=no" rel="noopener noreferrer" target="_blank">No</a>, <a href="https://dashboard.infracost.io/feedback/redirect?runId=&value=other" rel="noopener noreferrer" target="_blank">Other</a>
</sub>

Comment not posted to GitHub (--dry-run was specified)
