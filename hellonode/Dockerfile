FROM node:6-alpine
COPY server.js /app/
COPY run_tests.sh /usr/local/bin/ 
RUN chmod 777 /usr/local/bin/run_tests.sh
CMD ["node", "/app/server.js"]
