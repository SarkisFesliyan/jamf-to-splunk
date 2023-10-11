# jamf-to-splunk
This repo is has Jamf dashboards built with Splunk. Please replace the index information within the dashboard before pasting into your Splunk environment


## jamf_overview_xml requires the [Jamf app](https://splunkbase.splunk.com/app/4729/) at Version 1.0.10

## jamf_overview_json_2_10_7 requires the [Jamf app](https://splunkbase.splunk.com/app/4729/) at Version 2.10.7

## jamf_overview_json_2_10_7 requires the [Jamf app](https://splunkbase.splunk.com/app/4729/) at Version 2.10.9


# Install
- Requires you and your splunk team to already have the splunk integration setup and ingesting data.

1: Log into your Splunk evnironment

2: Select `Dashboards` across the top
![Screenshot 2023-10-11 at 11 48 24 AM](https://github.com/SarkisFesliyan/jamf-to-splunk/assets/65836961/ba8565fb-f30c-4c8a-b2be-1fba73f05156)

3: Select `Create new dashboard` 
![Screenshot 2023-10-11 at 11 48 57 AM](https://github.com/SarkisFesliyan/jamf-to-splunk/assets/65836961/3f53673c-2e10-4b22-a77a-cac6c1cb481d)

4: Select `Classic`
![Screenshot 2023-10-11 at 11 49 34 AM](https://github.com/SarkisFesliyan/jamf-to-splunk/assets/65836961/ed08b31e-5ea5-4015-867e-0fd8591f50ec)

5: Select `Source`
![Screenshot 2023-10-11 at 11 49 49 AM](https://github.com/SarkisFesliyan/jamf-to-splunk/assets/65836961/1ef5d481-2d15-4c6c-af86-86fde01b4f42)

6: Copy and paste the code from the github repo.

7: Use find and replace to rename `index = jamf` to whatever your actual index is called.
