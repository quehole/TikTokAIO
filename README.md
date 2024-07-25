# TikTokAIO

TikTokAIO is an automation script for interacting with TikTok using Selenium WebDriver. The script performs various actions such as adding views, likes (hearts), comments, followers, and shares to TikTok videos. It also includes functionality for refreshing and reloading the web pages.

## Features

- **Auto Views**: Increase views on a specific TikTok video.
- **Auto Hearts**: Add hearts (likes) to a TikTok video.
- **Auto Comments Heart**: Automatically heart the first comment on a TikTok video.
- **Auto Followers**: Increase followers for a TikTok account.
- **Auto Shares**: Share a TikTok video automatically.
- **Simple Reload**: Refreshes the page periodically.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/quehole/TikTokAIO.git
   cd TikTokAIO
   ```

2. **Install Dependencies**

   Make sure you have Python installed, then install the required packages:

   ```bash
   pip install selenium pyfiglet
   ```

3. **Download WebDriver**

   Download the appropriate version of [ChromeDriver](https://sites.google.com/chromium.org/driver/) for your operating system and place it in the project directory or specify the path in the script.

4. **Update Configuration**

   Modify the `vidUrl` variable in `main.py` to the TikTok video URL you want to interact with. Update the path to `chromedriver` if necessary.

## Usage

1. Run the script:

   ```bash
   python main.py
   ```

2. Choose an option from the menu:

   - `1` - Auto views (500 views)
   - `2` - Auto hearts
   - `3` - Auto (FIRST) comments heart
   - `4` - Auto followers
   - `5` - Auto share
   - `6` - Simple reload

   Enter the corresponding number to start the desired action.

## Notes

- Ensure that you handle captchas manually as the script will refresh the page if a captcha is detected.
- Modify the script according to your specific needs and ensure that you comply with TikTok’s terms of service.

## Author

Created by [quehole](https://github.com/quehole). For further assistance or questions, please refer to the GitHub repository.
