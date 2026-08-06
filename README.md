# Roblox Deployment Downloader (RDD)

## 🤔 Why I Made This Website

Roblox updates its client and launcher constantly, which can sometimes break local installations, make testing specific builds frustrating, or force users through restrictive installers.

I created this tool to give developers, modders, and players a fast, lightweight, and direct way to fetch official deployment binaries straight from Roblox CDN servers (`setup.rbxcdn.com`). Whether you need to download specific build versions using version hashes, grab files for custom channels, or bundle full client dependencies into a single ZIP file for easy archiving, this tool handles everything cleanly right inside your browser!

---

## 📖 How to Use

### 1. Basic Binary Downloads
1. Select your target **Binary Type** from the dropdown menu:
   * `WindowsPlayer` (Roblox Client for Windows)
   * `WindowsStudio` (Roblox Studio for Windows)
   * `MacPlayer` (Roblox Client for macOS)
   * `MacStudio` (Roblox Studio for macOS)
2. Leave **Channel** set to `LIVE` for standard public releases.
3. Click **Download** to trigger the official launcher file download directly from the CDN.

### 2. Downloading Specific Builds or Channels
1. Choose your **Binary Type**.
2. In the **Channel** input field, enter a custom deployment channel (such as `zlive` or `zcanary`) if you are testing non-standard builds.
3. *(Optional)* Paste a specific build hash into the **Version Hash** field (e.g., `version-a1b2c3d4e5f6`). If left blank, the tool automatically resolves the latest version hash for you.
4. Click **Download**.

### 3. Bundling Full Deployment Packages into a ZIP
1. Select your desired **Binary Type**.
2. Check the **Compress Zip** checkbox.
3. Choose a **Compression Level** from `1` (fastest processing) to `9` (maximum file reduction).
4. Click **Download**. The tool will automatically fetch all core package files, compress them directly inside your browser memory, and download the finished `.zip` archive.

### 4. Copying CDN Links
1. Set up your desired **Binary Type**, **Channel**, or **Version Hash**.
2. Click **Copy Link** to save the direct Roblox CDN URL straight to your clipboard for easy sharing or scripting!
