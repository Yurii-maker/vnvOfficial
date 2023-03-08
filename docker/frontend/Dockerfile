FROM node:18 AS development
ENV NODE_ENV development
# Add a work directory
WORKDIR /app
# Cache and Install dependencies

# Copy app files
COPY . /app
# Expose port
EXPOSE 3000
# Start the app


#TODO: RUN WHEN PRODUCTION CONFIG
#CMD [ "npm", "run-script", "build" ]
#CMD [ "npm", "start" ]