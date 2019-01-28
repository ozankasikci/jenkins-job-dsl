# jenkins-job-dsl

To start: `docker-compose up`

A jenkins instance gets fired up with installed packages, a predefined job gets mounted as a volume.

Running the seed job generates another job. The generated job can be started manually as there is no trigger defined by default.
