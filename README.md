# Mob-programming & the one-pager project

## Overview

This project, created as part of the Web Development Bootcamp at Technigo, is a business one-pager website developed collaboratively by a team of 5 individuals using mob-programming techniques. The project was completed within a few hours during the introductory day of the Bootcamp. Emphasis on simplicity and quick implementation to meet project goals within the given timeframe. The brief for the project included: having an engaging image or video header, a signup form and an accordion for the Q&A section, made with some basic logics of JavaScript. 

## Business one-pager website

Our team chose to create a dedicated webpage focused on dog adoption. We designed a user-friendly form for individuals interested in adoption to easily submit their personal details. To facilitate form testing and debugging, we utilize the httpbin.org service as the form action endpoint. This allows us to observe and validate the data sent from the adoption form (the /anything endpoint on HTTPBin is a versatile tool for testing and debugging HTTP requests which echoes back information about the received request). 

We implemented a dynamic FAQ section using JavaScript logic to address common dog adoption questions. This JavaScript code snippet enhances user interactivity by allowing the toggling of a class, "active," on two specified HTML elements (#section1 and #section2). The code defines toggle functions for each element, and these functions are triggered by click events on the corresponding elements. This implementation provides a straightforward way to toggle visual styles, contributing to a more dynamic and engaging user experience.

## The problem

After the intro days, I decided to add some improvements to our intro days project. Instead of an image in the header, I decided to add a video from <a href="https://www.pexels.com/videos/" target="a_blank"> Pexels </a> to my header. It required using <video> tag instead of placing the image as a background of the div. Then the video needed to be adjusted for each of three sizes of the screen to make this project fully responsive. 

## View it live
Here you will see it <a href="https://leafy-duckanoo-0d53b4.netlify.app/" target="_blank"> live </a>.
