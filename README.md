# jenkins-job-dsl

To start: `docker-compose up`

The test should run without any other action.

A jenkins container gets fired up with packages specified in `plugins.txt`. A predefined job gets mounted as a volume (seed-job).

Running the seed-job fetches job dsl from the public repo and generates another job. The generated job can be started manually as there is no trigger defined by default. Jenkins url is: `localhost:89`
