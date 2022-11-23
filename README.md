# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

### How to run this project?

After cloning the project, open a terminal and run:

```
npm i
```

After the dependencies are installed, run:

```
npm run dev
```

The API to apply a filter to the image, will be available at the URL: http://localhost:8082/filteredimage

To test you must pass an image URL, for example:

```
http://localhost:8082/filteredimage?image_url=https://images.pexels.com/photos/162203/panthera-tigris-altaica-tiger-siberian-amurtiger-162203.jpeg
```

Image before filter

![cat](https://github.com/msinghcoder/udacity-image-filter-starter-code/blob/master/deployment_screenshots/image_before_filter.jpeg) 

Image after filter

![cat-filter](https://github.com/msinghcoder/udacity-image-filter-starter-code/blob/master/deployment_screenshots/image_after_filter.jpeg) 


### AWS Elastic Beanstalk

 Elastic Beanstalk App URL: 
 
http://image-filter-starter.us-east-1.elasticbeanstalk.com

http://image-filter-starter.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://images.pexels.com/photos/162203/panthera-tigris-altaica-tiger-siberian-amurtiger-162203.jpeg
