# IoT Honeypot

This repository contains a simple IoT honeypot for application layer running on Constrained Application Protocol (CoAP).

## Features

- **Attack**: The `Attacks` directory contains various attacks that were attempted on the Honeypot. In case of an attack, the details of the attacker are collected and saved into the logs file.

- **CoAP Honeypot**: The `CoAP` directory includes a Constrained Application Protocol (CoAP) honeypot setup.

- **Web Interface**: The `website` directory hosts a simple web interface which acts as the application that will be under attack and will be the honeypot.

## Getting Started

To set up and run the honeypot locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/WahajK/Deployed_Honeypot.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Deployed_Honeypot
   ```

3. **Install dependencies**:

   Ensure you have Python installed. Then, install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the honeypot**:

   ```bash
   python wsgi.py
   ```

   This will start the honeypot, and it will begin logging attack attempts.

5. **Access the web interface**:

   Open your browser and navigate to `http://localhost:5000` to view the website and run attakcs to create logs.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

## Resources

For more information on honeypots and their deployment, consider the following resources:

- [Awesome Honeypots](https://github.com/paralax/awesome-honeypots): A curated list of honeypot resources.

- [CommunityHoneyNetwork](https://communityhoneynetwork.readthedocs.io/): Documentation on deploying and managing honeypots.

- [Protecting Your Network With Honeypots](https://tcm-sec.com/protecting-your-network-with-honeypots/): An article on using honeypots for network security.

- [Deploying a Honeypot on AWS](https://medium.com/@sudojune/deploying-a-honeypot-on-aws-5bb414753f32): A guide on setting up a honeypot in the AWS environment.

- [Adventures in Running a Honeypot Hive](https://jonathancilley.hashnode.dev/adventures-in-running-a-honeypot-hive): An experience report on deploying multiple honeypots.

- [Deploying T-Pot Honeypot in Azure Cloud](https://medium.com/@weexplore2learn/deploying-t-pot-honeypot-in-azure-cloud-enhancing-cybersecurity-measures-f24b4a21493a): A comprehensive guide on deploying the T-Pot honeypot in Azure.
