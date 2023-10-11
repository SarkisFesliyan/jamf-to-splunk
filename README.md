# jamf-to-splunk
This repo is has Jamf dashboards built with Splunk. Please replace the index information within the dashboard before pasting into your Splunk environment


## jamf_overview_xml requires the [Jamf app](https://splunkbase.splunk.com/app/4729/) at Version 1.0.10

## jamf_overview_json_2_10_7 requires the [Jamf app](https://splunkbase.splunk.com/app/4729/) at Version 2.10.7

## jamf_overview_json_2_10_7 requires the [Jamf app](https://splunkbase.splunk.com/app/4729/) at Version 2.10.9


# Install
- Requires you and your splunk team to already have the splunk integration setup and ingesting data.

1: Log into your Splunk evnironment

2: Select `Dashboards` across the top

3: Select `Create new dashboard` 

4: Select `Classic`

5: Select `Source`

6: Copy and paste the code from the github repo.

7: Use find and replace to rename `index = jamf` to whatever your actual index is called.