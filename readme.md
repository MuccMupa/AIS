FROM KURPATOV WITH LOVE

USUALLY RUN: docker-compose up
USUALLY reRUN without downloads dockers: docker-compose up --no-deps --build




##############################################
# Kogda-to bilo nujno

sudo usermod -aG docker your-user
# RUN cd /usr/local/src && wget -qO- https://get.docker.com/ | sh
	RUN usermod -aG docker root