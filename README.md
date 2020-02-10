# prometheus

## Prometheus concepts

### Metrics

There are currently only three types of metric supported by Prometheus. These are:

* Counter — A simple monotonically incrementing type; basically use this for situations where you want to know “how many times has x happened”.

* Gauge — A representation of a metric that can go both up and down. Think of a speedometer in a car, this type provides a snapshot of “what is the current value of x now”.

* Histogram — Ok, this is the complex one, this represents observed metrics sharded into distinct buckets. Think of this as a mechanism to track “how long something took” or “how big something was”.

### Prometheus resources

Prometheus For Beginners https://itnext.io/prometheus-for-beginners-5f20c2e89b6c

Robust Perceptions Blog  https://www.robustperception.io/blog

Roald Nefs Awesome-Prometheus Github Repo https://github.com/roaldnefs/awesome-prometheus

Video: Prometheus: Design and Philosophy https://www.youtube.com/watch?v=QgJbxCWRZ1s&feature=youtu.be