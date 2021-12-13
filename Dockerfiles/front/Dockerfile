FROM node:17.1.0
RUN git clone "https://github.com/Lutenruto/rust.git"
WORKDIR "/rust/frontend"
RUN npm install
RUN npm run build
CMD npm start