# SE4GEO Project

**Project Assignment of the course "Software Engineering for Geoinformatics" at Politecnico di Milano.**

This is an Open-Source Application designed to provide users with information on air pollution and pollutants of European cities. Our main goal is to create a collaborative platform where users can actively contribute to data enrichment, the implementation of new functionalities, and the development of custom models.

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

The application required Anaconda or mamba being installed. 

### Installation

1. Clone the repo
  ```sh
  git clone https://github.com/carls31/SE4GEO-Lab.git
  ```
2. Set up the python environment using the command:
  ```sh
  conda env create -f se4g.yml 
  ```
  If you are using mamba instead launch the command:
  ```sh
  mamba env create -f se4g.yml 
  ```

The main functions are defined in the file `'se4g_helper.py'`, and the dashboard is included in `'se4g_JupyterDash_demo.ipynb'`.

Documentation files:
 * GRUPPO_GEO_RASD.pdf
 * GRUPPO_GEO-DD.pdf
 
## Usage

Login and go to 2. otherwise Register following the instructions in 1.
1. Select the user profile
     * GEO User: This is an Environmental Engineer who, in addition to having access to the dashboard, can also download existing data and, most importantly, upload new data. This user has the ability to contribute to the enrichment of available data.
     * MTM User: This profile is dedicated to Mathematical Engineers or professionals such as Data Scientists who can use the dashboard to visualize available data and develop numerical, computational, or statistical models. This user has the ability to utilize the data for analysis and the development of custom models.

     * :warning:  default basic profile will be available that does not require registration, allowing users to access the dashboard without further formalities.

Please wait for your registration request to be approved.

2. Select a city in Europe of which you want to retrieve data
 * dashboard daily mean
 * dashboard select day by user
 * histograms
 * select pollutant and shows timeseries of all the cities 
 * correlation matrix

Feel free to explore and utilize these features for your analysis and model development.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/new`)
3. Commit your Changes (`git commit -m 'Add some Feature'`)
4. Push to the Branch (`git push origin feature/new`)
5. Open a Pull Request

## License

Distributed under the GNU General Public License v3.0. See `LICENSE.txt` for more information.
