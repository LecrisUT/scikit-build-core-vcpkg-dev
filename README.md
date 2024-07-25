# scikit-build-core-vcpkg-dev
minimal reproducible environment to test orchestrate scikit-build-core with vcpkg

## HOWTO
1. clone repo and open in vscode;
2. Dev containers: open folder in container
3. cd `molpy` and `pip install -e .` expect to raise an error;
4. cd `molpy/molcpp` and `cmake --preset=dev-linux` expect work fine

## changelog

add workflow