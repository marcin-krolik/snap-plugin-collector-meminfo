# Example tasks

[This](task-mem.json) example task will collect metrics from **meminfo** and publish
them to file.  

## Running the example

### Requirements 
 * `docker` and `docker-compose` are **installed** and **configured** 

Running the sample is as *easy* as running the script `./run-mock-meminfo.sh`.

## Files

- [run-mock-meminfo.sh](run-mock-meminfo.sh)
    - The example is launched with this script     
- [task-mem.json](task-mem.json)
    - Snap task definition
- [.setup.sh](.setup.sh)
    - Verifies dependencies and starts the containers.  It's called 
    by [run-mock-meminfo.sh](run-mock-meminfo.sh).