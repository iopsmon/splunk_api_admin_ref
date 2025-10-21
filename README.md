# Splunk REST API Quick Reference (dc_splunk_api_guide.html)

Short summary
-------------
A lightweight, single-page HTML reference that collects common Splunk REST API / SPL snippets for Splunk administrators. Designed for quick lookup, copy-to-clipboard, and paste into the Splunk Search bar or Monitoring Console.

Key features
------------
- Sidebar navigation for quick access to sections
- Ready-to-copy REST + SPL snippets (Config, Resources, Storage, Search, Splunk Apps, Access, Deployment, Utilities)
- Copy and Toggle controls for each snippet
- Clean, responsive UI optimized for readability
- Lightweight CSS/JS; no external libraries
- Timestamped generation shown in the footer

Sections included
-----------------
- Config & TLS checks
- Host and Splunk process resource usage
- Storage / Index metrics and retention
- Saved searches and search analysis
- Splunk Apps (installed apps and metadata)
- Access & tokens (user and role checks)
- Deployment / client phone-home checks
- Utilities & recommended export cadence

Usage
-----
1. Open `dc_splunk_api_guide.html` in a browser.
2. Copy any snippet using the "Copy" button, then paste into the Splunk Search bar or REST client.
3. Run snippets from a Search Head or the Monitoring Console for best coverage.
4. Use `| outputcsv` in Splunk to capture results for further analysis.

Customization
-------------
- Edit or add SPL snippets directly in the `<pre>` blocks.
- Adjust styling in the `<style>` section.
- Add new navigation items by updating the sidebar `.toc` links and adding corresponding `<section>` elements.

Deployment
----------
- Store the HTML file on Documentation server, internal wiki, or local workstation.
- Can be shared with the operations team as a static reference.

Author / Attribution
--------------------
Created for Splunk administrators. Filename: `dc_splunk_api_guide.html`

License
-------
Use internally. Modify as needed for local procedures and environment.
