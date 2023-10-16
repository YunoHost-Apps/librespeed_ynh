* Any known limitations, constrains or stuff not working :
    * Please visit [Troubleshooting, common problems, known limitations](https://github.com/librespeed/speedtest/wiki/Troubleshooting,-common-problems,-known-limitations) for more informations.
    * Important: ID obfuscation currently only works on 64-bit PHP! You might want to set `$redact_ip_addresses` to true in `results/telemetry_settings.php`, this way, all IP addresses will be removed from the telemetry for better privacy. This is disabled by default.

* Other infos that people should be aware of :
    * A basic front-end for visualizing and searching tests by ID is available in `__DOMAIN____PATH__/results/stats.php`. A password is asked to you during installation steps to access this page. 
