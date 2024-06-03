# ml-project
![GitHub License](https://img.shields.io/github/license/0rlych1kk4/ml-project)

# create a new project
  cargo new --bin ml-project
#
# Add the following in the Cargo.toml file, under [dependencies]:
  linfa = "0.6.0"
  linfa-trees = "0.6.0"
  linfa-datasets = { version = "0.6.0", features = ["iris"] }
#
# Lastly, run the command:
  cargo build
 
# To Prepare the Dataset
Machine Learning models requires external data to be trained. I provided an sample csv data for this exercise but later you’ll          learn how to prepare your own dataset from a csv file.
You can get a dataset from Kaggle.

Once you have downloaded the dataset, extract the csv file into your project’s src folder.
.
├── Cargo.lock
├── Cargo.toml
└── src
    ├── heart.csv
    └── main.rs

## License
This project is licensed under the GitHub License. See the [LICENSE](LICENSE) file for details.
