# gve_devnet_catalyst_center_custom_issues_and_events_dashboard
React web-app made to customize the filtering functionality of both issue and event logs in catalyst center. 


## Contacts
* Rey Diaz

## Solution Components
*  DNA center SDK
*  React
*  Electron
*  FastAPI

## Related Sandbox Environment

This sample code can be tested using a Cisco dCloud demo instance that contains ** *[Catalyst Center](https://devnetsandbox.cisco.com/DevNet/catalog/Catalyst-Center-Always-On)* **


## Prerequisites
**Catalyst Center Credentials**: In order to use the Catalyst Center APIs, you need to make note of the IP address, username, and password of your instance of Catalyst Center. Note these values to add to the credentials file during the installation phase.


## Installation/Configuration

 1. Clone this repository with `git clone [repository name]`. To find the repository name, click the green `Code` button above the repository files. Then, the dropdown menu will show the https domain name. Click the copy button to the right of the domain name to get the value to replace [repository name] placeholder.
![git-clone.png](git-clone.png)

### Backend

 1. Navigate to the `Backend` directory.
 2. Set up a virtual environment: `python -m venv venv`
 3. Activate the virtual environment:
   - Windows: `.\venv\Scripts\activate`
   - Unix or MacOS: `source venv/bin/activate`

 4. Install dependencies: `pip install -r requirements.txt`

### Frontend

 1. Navigate to the `src` directory.
 2. Install Node.js dependencies: `npm install`


## Usage

### Running the Backend
 1. Ensure the virtual environment is activated.
 2. Start the FastAPI server: `python main.py`

### Running the Frontend
1. In the `src` directory, start the React app: `npm start`
2. The application should be accessible at `localhost:3000` (default React port).


# Screenshots

![/IMAGES/0image.png](/IMAGES/0image.png)

### LICENSE

Provided under Cisco Sample Code License, for details see [LICENSE](LICENSE.md)

### CODE_OF_CONDUCT

Our code of conduct is available [here](CODE_OF_CONDUCT.md)

### CONTRIBUTING

See our contributing guidelines [here](CONTRIBUTING.md)

#### DISCLAIMER:
<b>Please note:</b> This script is meant for demo purposes only. All tools/ scripts in this repo are released for use "AS IS" without any warranties of any kind, including, but not limited to their installation, use, or performance. Any use of these scripts and tools is at your own risk. There is no guarantee that they have been through thorough testing in a comparable environment and we are not responsible for any damage or data loss incurred with their use.
You are responsible for reviewing and testing any scripts you run thoroughly before use in any non-testing environment.
