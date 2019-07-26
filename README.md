git clone https://github.com/webethics/NodeDockerTest.git

docker build -t firstapp .

docker run -p 8081:8081 firstapp	 