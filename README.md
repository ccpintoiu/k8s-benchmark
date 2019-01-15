# k8s-benchmark
bare metal vs aws



Run netperf_tester.go:

git clone https://github.com/kubernetes/contrib/

cd contrib/netperf-tester

go run netperf_tester.go -number 1000 -kubectl kubectl -output 1000.csv
