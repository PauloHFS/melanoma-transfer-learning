# melanoma-transfer-learning

## Requirements

- tensorman

## How to run

1. Run the following command to start a docker container with jupyter notebook running on port 8888.

  ```bash
  tensorman run -p 8888:8888 --gpu --python3 --jupyter  bash
  ```

2. Run the following command to start jupyter notebook.

  ```bash
  jupyter notebook --ip=0.0.0.0 --no-browser
  ```
