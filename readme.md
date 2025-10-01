## Azure infra as code artifacts: mainly ARM templates.

This repo contains many ARM templates. The intent is:
- To provide templates which are each responsible for exactly one Azure resource type - no giant spaghetti templates mingling resources, which are only ever useful once. Instead, these are templates which can be assembled flexibly in... scripts, infrastructure deployment pipelines, etc.
- To heavily parameterize templates so they are very flexible for different scenarios
- To include lots of conditional logic (ARM functions etc.) to make templates still more flexible for different scenarios

These ARM templates have been used in several production projects, so they have been thoroughly tested and have successfully deployed many Azure resources.

---

### PLEASE NOTE FOR THE ENTIRETY OF THIS REPOSITORY AND ALL ASSETS
#### 1. No warranties or guarantees are made or implied.
#### 2. All assets here are provided "as is". Use at your own risk. Validate before use.
#### 3. We assume no liability whatsoever, and will not provide support, for any use of these assets outside of a contractual engagement with AXON10 LLC.
#### 4. Use of the assets in this repo in your Azure environment may or will incur Azure usage and charges. You are completely responsible for monitoring and managing your Azure usage.

---

Unless otherwise noted, all assets here are original to and authored by AXON10 LLC. Feel free to examine, learn from, comment, and re-use (subject to the above) as needed and without intellectual property restrictions.

If anything here helps you, attribution and/or a quick note is much appreciated.
