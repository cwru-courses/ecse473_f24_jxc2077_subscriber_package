
## Repository Structure


- **subscriber_package**: Contains the C++ implementation of the Subscriber.
- **subscriber_package_py**: Contains the Python implementation of the Subscriber.

## Running the Examples

### Python Version

1. **Run the Python Publisher and Subscriber**:
   - Ensure that both `publisher_package_py` and `subscriber_package_py` are located at the same directory level as `publisher_package` and `subscriber_package`.
   - Execute the Publisher:
     ```bash
     python3 ./devel/lib/publisher_package_py/publisher_code.py
     ```
   - Execute the Subscriber:
     ```bash
     python3 ./devel/lib/subscriber_package_py/subscriber_code.py
     ```


     ```

## Notes

- This repository's structure is designed for the ease of assignment submission. Ensure that the packages (both C++ and Python versions) are maintained at the same hierarchical level in your workspace to avoid any runtime issues.
- Make sure you have installed all necessary dependencies and your ROS environment is correctly sourced before running the examples.

