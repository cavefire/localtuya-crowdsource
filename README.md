![logo](https://github.com/cavefire/localtuya-crowdsource/blob/master/img/logo-small.png)

# LocalTuya Home Assistant Integration

This is a custom integration for Home Assistant designed to handle Tuya-based devices locally, enhancing privacy and control.

---

## Purpose of This Fork

The primary goal of this fork is to simplify the setup of Tuya devices by leveraging community support for device mapping. By collaborating, this repository will grow to include configurations for various devices, making the setup process faster and easier.

The server source code, used for this project can be found here: [localtuya-crowdsource-server](https://github.com/cavefire/localtuya-crowdsource-server)

### How to Contribute

To contribute, simply install this forked repository instead of the original "localtuya." Your devices will continue to function as before, but each time you load the integration, your device configuration will be sent to a server for review. **Only device configurations are stored**—no personal information or device names are collected.

Once approved, your configuration will be added to the repository, allowing everyone, including you, to benefit from pre-configured device mappings.

### About the Developer

While not a Home Assistant expert, I come from a background in C and Assembly. Although Python is new for me, I’ve created this fork to help streamline device setup for myself, my family, and friends who, like me, manage many Tuya devices. This project is an effort to make Tuya device configuration a one-time task that’s easy for everyone.

**Ways you can help with this project:**
1. **Contribute your device configuration** by using this integration.
2. **Support with code contributions** if you have experience.

## Current features:
- Uploading device configurations to a server for review.
- On device setup you can choose to set up the device by using the configuration from this repository.

## Roadmap

1. **Configuration Submission Control**: Currently, device configurations are automatically submitted to the server on each integration load. In the future, I'd like to add a button allowing users to submit their configurations manually, giving users more control over their data and reducing server load.
2. **Automatic Handling of New Configurations**: Ideally, I would like a streamlined way to manage new configurations, perhaps through automation or merge requests in this repository.
3. **Auto-Discovery and One-Click Setup**: Implementing auto-discovery for Tuya devices would simplify the setup process even further, allowing for a single-click setup.
4. **Collect cloud meta data**: Collecting meta data about the devices using your tuya account (locally on your home assistant instance) would allow us to make the device list accessible, so you can see which devices are already supported and which are not, maybe making it easier to decide which devices to buy.

Most important to me is **your data privacy**. The only reason for this project is to leave the cloud. Having me or anyone else collect personal data would only move the data to the next cloud. I will never collect any personal data, and I will make sure that the data I collect is as minimal as possible.

---

# Installation Guide

1. **Add Custom Repository in HACS**:
   - Open **HACS**.
   - Click the "..." in the top-right corner.
   - Select "Custom repositories."
   - Add this repository URL and select "Integration" as the type.
   - Click "Add."

2. **Install the Integration**:
   - Search for "Local Tuya - Crowdsource" in the HACS store and follow the installation steps.

---

# Configuration Instructions

For more detailed configuration instructions, please refer to the original repository’s [Usage Guide](https://github.com/rospogrigio/localtuya?tab=readme-ov-file#usage).

---

# Code Contributions

For any functionality unrelated to the crowdsource feature, please contribute to the original repository [here](https://github.com/rospogrigio/localtuya). This fork will be updated regularly with the latest changes from the original.

In the future, if this fork becomes sufficiently populated with device configurations, stable, and user-friendly, we can explore merging back into the main repository.

### Contact

Feel free to reach out to me on Discord [@cavefire](https://mine.li/discord_user) if you’d like to discuss contributions or help with development around the crowdsource feature.


# Support
Instead of supporting me, please consider supporting the original developer. His links can be found here or in the original repository at the bottom.
<a href="https://www.buymeacoffee.com/rospogrigio" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
<a href="https://paypal.me/rospogrigio" target="_blank"><img src="https://www.paypalobjects.com/webstatic/mktg/logo/pp_cc_mark_37x23.jpg" border="0" alt="PayPal Logo" style="height: auto !important;width: auto !important;"></a>