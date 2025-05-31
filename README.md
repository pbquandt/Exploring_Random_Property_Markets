# Exploring Random Property Markets 

<img src="https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/readme_img/hero_image.jpg" alt="hero image" width="800"/>

## Introduction

This project was originally developed as part of a technical assignment during a recruitment process for a property letting service.
Due to confidentiality agreements, I am not permitted to disclose the company name or share the original dataset provided.

To replicate the structure and logic of the original task while respecting data privacy, I used the Faker Python library to generate artificial data.

Please note that every time the notebooks are run locally, a new synthetic dataset will be generated. As a result, the specific interpretations and insights from the original analysis have been removed, since they only applied to the real-world data.

If you are interested in reviewing the original project (under confidentiality), it is available upon request.



<img src="https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/readme_img/note_exe_1.png" alt="notebook example screen shot" width="400"/>
<img src="https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/readme_img/note_exe_2.png" alt="notebook example screen shot" width="400"/>
<img src="https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/readme_img/note_exe_3.png" alt="notebook example screen shot" width="400"/>
<img src="https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/readme_img/note_exe_4.png" alt="notebook example screen shot" width="400"/>
<img src="https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/readme_img/note_exe_5.png" alt="notebook example screen shot" width="400"/>
<img src="https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/readme_img/note_exe_6.png" alt="notebook example screen shot" width="400"/>


   
**Main Tech Stack**:

- Python (data analysis and engineering)
- PostgreSQL (database management)
- SQL queries
- Faker, Pandas, NumPy (data creating & processing)
- Matplotlib, Seaborn (data visualization)

![image](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![image](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![image](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![image](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![image](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
![image](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)


## Table of Contents

1. [N01 Data Creation, Exploration & Cleaning](https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/N01_data_cleaning.ipynb)
2. [N02 Initializing a PostgreSQL database and creating schemas for data exploration](https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/N02_initiating_database.ipynb)
3. [N03 SQL Queries & Data Visualization](https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/N03_data_visualisation.ipynb)
4. [N04 Analysis of a randomly selected city](https://github.com/pbquandt/Exploring_Random_Property_Markets/blob/master/N04_random_city_data_exploration.ipynb)


## Installation

To run **Exploring Random Property Markets** project locally, follow these steps:

1. Create a dedicated virtual environment (optional)
2. Clone the repository:
   ```bash
   git clone https://github.com/pbquandt/Exploring_Random_Property_Markets.git
   ```
3. Navigate to the project directory:
   ```bash
   cd Exploring_Random_Property_Markets 
   ```
4. Use the `requirements.txt` file to install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
5. Install [PostgreSQL](https://www.postgresql.org/)  
   There are several options available for installing PostgreSQL on your local machine, depending on whether you're using a Mac or a PC.  
   If you don't have PostgreSQL installed yet, I recommend searching for a suitable tutorial on Google or YouTube. You can also ask ChatGPT for step-by-step instructions,  
   specifying the type of computer you're using and your operating system (Windows, macOS, Linux, etc.).
    ####
   **Key information:**  

   - Make sure your PostgreSQL version is 14 (`postgresql@14`).  
   - When setting up PostgreSQL for the first time, remember to replace credentials in attached `db_auth.py` file, with our local Postgres BD credentials:  
     - **Username**: `USER`  
     - **Password**: `PASSWORD`  
     - **Port**: `5432` (default)  
     - **Host**: `localhost` (default)
    ####
   **Some useful links:**  
   - Windows: [https://www.w3schools.com/postgresql/postgresql_install.php](https://www.w3schools.com/postgresql/postgresql_install.php)  
   - Mac: [https://www.youtube.com/watch?v=Z-iM7hUdBSg](https://www.youtube.com/watch?v=Z-iM7hUdBSg)  
   - Mac (via Homebrew): [https://www.moncefbelyamani.com/how-to-install-postgresql-on-a-mac-with-homebrew-and-lunchy/](https://www.moncefbelyamani.com/how-to-install-postgresql-on-a-mac-with-homebrew-and-lunchy/)

   

## Potential Issues 

This project was done on a Mac. If you would like to run it on a PC, please make sure to appropriately adjust the path separators.


## Contributing

If you'd like to contribute to **Exploring Random Property Markets**, follow these steps:

1. Fork the repository
2. Create a new branch for your changes
3. Implement your changes
4. Write tests to cover your changes
5. Run the tests to ensure they pass
6. Commit your changes
7. Push your changes to your forked repository
8. Submit a pull request


## Authors and Acknowledgments

**Exploring Random Property Markets** was created by [**Piotr B. Quandt**](https://github.com/pbquandt)

### Hero Image
- Cover image of this document - [
Abdullah Ghatasheh](https://www.pexels.com/photo/aerial-shot-of-city-1666362/)


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


## Contact
For questions or comments, please contact [**Piotr B. Quandt**](https://github.com/pbquandt) at [pbquandt@gmail.com](mailto:pbquandt@gmail.com)

