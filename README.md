# ml-project
#
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
  
