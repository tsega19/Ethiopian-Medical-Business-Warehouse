# ETH MedData Warehouse
ETH MedData Warehouse is a data warehouse project that is designed to collect, store, and analyze medical data from various sources in Ethiopia. The project involves web scraping, data cleaning, transformation, and analysis, and also includes a FastAPI application for data visualization and visualization. The project also includes a FastAPI application for data visualization and visualization.


## Project Structure

- **notebooks/**: Contains Jupyter notebooks for data exploration and analysis.
- **data/**: Stores raw and processed data files.
- **scripts/**: Includes Python scripts for data cleaning, transformation, and other utilities.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/tsega19/Ethiopian-Medical-Business-Warehouse.git
   cd Ethiopian-Medical-Business-Warehouse
   ```

2. **Set up the virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the initial data processing**:
   ```bash
   python scripts/data_cleaning_transformation.py
   ```

5. **Explore the data using Jupyter notebooks**:
   ```bash
   jupyter notebook
   ```

## Using the Starter Project

Try running the following commands:
- `dbt run`: Execute the dbt models.
- `dbt test`: Run tests on the dbt models to ensure data integrity.

## Resources

- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction).
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers.
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support.
- Find [dbt events](https://events.getdbt.com) near you.
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices.

## Contributors

We welcome contributions to this project. Please feel free to submit issues, fork the repository, and create pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
