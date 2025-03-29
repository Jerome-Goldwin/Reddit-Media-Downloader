Reddit Media Downloader

📌 Description

This Bash script automates the process of downloading media (images/videos) from Reddit posts using wget and gallery-dl. It extracts direct media links from Reddit pages and downloads them efficiently.

🔧 Requirements

Make sure you have the following dependencies installed before running the script:

sudo apt update && sudo apt install wget
pip install gallery-dl

📥 Installation

Clone the repository and navigate to the project folder:

git clone https://github.com/yourusername/reddit-media-downloader.git
cd reddit-media-downloader
chmod +x reddit_downloader.sh

🚀 Usage

Run the script with a Reddit post URL as an argument:

./rdt "https://www.reddit.com/r/example/comments/postid/"

By default, downloaded media will be saved to a specified directory (DLDIR).

⚙️ Features

Extracts direct media links from Reddit posts

Supports both single image/video posts and galleries

Automates downloading using gallery-dl

Uses awk for efficient text processing

🛠️ Troubleshooting

If you encounter issues, ensure gallery-dl is installed correctly:

gallery-dl --version

Check if the Reddit post contains media and is publicly accessible.

📜 License

This project is open-source and licensed under the MIT License.
