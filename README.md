# Mapping Data and Knowledge for Citizen Science

## Contents
+ [Goal](#goal)
+ [Who should attend](#who-should-attend)
+ [Prerequisites](#prerequisites)
+ [Objectives](#objective)
+ [Schedule](#duration)
   - [Day 1 - Introduction to the Stack](#day-1-introduction)
   - [Day 2 - Working Collaboratively](#day-2-working-collaboratively)
   - [Day 3 - Setting Up the Backend](#day-3-setting-up-the-backend)
   - [Day 4 - Mapping App](#day-4-mapping-app)
   - [Day 5 - Mapping App contd.](#day-5-mapping-app)

## Goal

This workshop will provide an overview of the current state of mapping technologies, and teach how to build an offline-capable mapping app that can be used to record field data and then sync-ed to a server when network becomes available. Additionally, by fully understanding what makes today’s applications do their magic, the attendees will also learn about the sociocultural and legal issues that are important in determining who can access and reuse data, and the steps that will minimize or eliminate hurdles.

## Who should attend

This is a hands-on intermediate-to-advanced workshop to learn how to create map-based data analysis and visualization applications. It will introduce and take you through advanced concepts in data acquisition, management and use, and also legal aspects (open source vs. proprietary), but we don't want to classify the workshop as *advanced* because the apps you will build will not be suitable for launching a company and becoming a millionaire. However, you will certainly learn enough to build your own apps for **education** and **citizen science**. It is a workshop for you if you are interested in using software tools to build tools and manage and analyze data, and are also interested in the non-technical factors that may affect your work both negatively or positively. This is not a delivery-only workshop, but a workshop leading to making an app or two. Therefore the participants need to have an interest in making or learning-by-making.

## Prerequisites

+ Desire to build open source web mapping applications
+ Familiarity with Unix-style commands
+ Working knowledge of JavaScript, server-side/asynchronous programming a plus
+ Knowledge of HTML and CSS
+ Have own laptop with [node.js](http://nodejs.org), [npm](http://npmjs.com), the node package manager, and a code editor of your choice installed. If you have a Mac, you will need to have [Xcode](https://developer.apple.com/xcode/) installed.

## Objective

Our objective is to not just teach you about the technology and workflow but also the associated sociocultural and legal issues, and in that process, hopefully help you appreciate why choosing the right license, being open, and collaborating with others is very important when working on the web. By the end of the workshop, participants should:

+ Learn how to find free and open geo data
+ Understand how to create an interactive map from data
+ Be able to debug a web mapping application
+ Know how to choose a data dissemination method
+ Be able to conceptualize a full stack web application
+ Work collaboratively on coding projects
+ Know how to choose a license
+ Become familiar with the legal issues surrounding data acquisition, manipulation, and use

### Why JavaScript?

As you can see from this README, we will be using many different technologies. But the glue language for all these technologies will be primarily JavaScript. We have chosen `js` because we want to avoid language wars (none of us believe that any one language can do everything), `js` is present on everyone's computer because it is the primarily programming language in the browser, and learning server-side `js` can help one do both server and client work with the same language. But, more than anything, `js` is a modern, capable, fast language that is fun to develop with, and has a very rich community of developers who contribute reusable code in the form of packages that can be easily installed using `npm`.

## Duration

The full workshop will last five days. Each day will be a mix of mainly technical subject matter supplemented with relevant social/cultural/legal aspects at the end of the day. The structure of the workshop is as shown below:

### Day 1: Introduction

<table width="100%">
	<thead>
		<tr>
			<th width="30%">Time</th>
			<th>Activity</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>09:00 AM-09:30 AM</td>
			<td>Intro and goals<br>
				<i>Who we are and workshop goals</i>
			</td>
		</tr>
		<tr>
			<td>09:30 AM-10:30 AM</td>
			<td>Overview of the web mapping workflow and stack<br>
				<i>How to go from data to a sharable URL</i>
			</td>
		</tr>
		<tr>
			<td>10:30 AM-11:00 AM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>11:00 AM-12:30 PM</td>
			<td>Overview of the technologies of the stack<br>
				<i>Introduce the variety of technologies that can be used in each piece of the stack—libraries such as jQuery vs. an model-view-controller (MVC) framework vs. rolling your own, and different backends and why you might use each</i>
			</td>
		</tr>
		<tr>
			<td>12:30 PM-02:00 PM</td>
			<td><i>lunch</i></td>
		</tr>
		<tr>
			<td>02:00 PM-03:30 PM</td>
			<td>Dissecting a mapping app<br>
				<i>Demonstrate mapping apps, and also introduce browser-based dev tools for dissecting and debugging. After a couple of examples, point the class to the URL of a mapping app and have them figure out which technology it uses and how it is assembled.</i>
			</td>
		</tr>
		<tr>
			<td>03:30 PM-04:00 PM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>04:00 PM-05:30 PM</td>
			<td>Technologies behind a mapping app<br>
				<i>Computer preparation, installation of software `nodejs`, <a href='http://postgis.org'>PostGIS</a>, <a href='http://www.git-scm.com'>git</a>, <a href='http://github.com'>Github</a> or <a href='http://gitlab.com'>Gitlab</a>, environment, setting up a repository, <a href='http://qgis.org'>QGIS</a>, <a href='http://gdal.org'>GDAL</a></i>
			</td>
		</tr>
	</tbody>
</table>

### Day 2: Working Collaboratively

<table width="100%">
	<thead>
		<tr>
			<th width="30%">Time</th>
			<th>Activity</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>09:00 AM-10:30 AM</td>
			<td>git and Gitlab/Github<br>
				<i>all about version control and social coding</i>
			</td>
		</tr>
		<tr>
			<td>10:30 AM-11:00 AM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>11:00 AM-12:30 PM</td>
			<td>Asking questions, finding answers<br>
				<i><a href='http://stackoverflow.com'>Stackoverflow</a>, mailing lists</i>
			</td>
		</tr>
		<tr>
			<td>12:30 PM-02:00 PM</td>
			<td><i>lunch</i></td>
		</tr>
		<tr>
			<td>02:00 PM-03:30 PM</td>
			<td>Project websites<br>
				<i>Telling the world about your work</i>
			</td>
		</tr>
		<tr>
			<td>03:30 PM-04:00 PM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>04:00 PM-05:30 PM</td>
			<td>Working collaboratively in the open<br>
				<i>Why communities matter and how to be involved</i>
			</td>
		</tr>
	</tbody>
</table>

### Day 3: Setting Up the Backend

<table width="100%">
	<thead>
		<tr>
			<th width="30%">Time</th>
			<th>Activity</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>09:00 AM-10:30 AM</td>
			<td>Data acquisition<br>
				<i>Where to find data: portals, APIs, scraping.</i>
			</td>
		</tr>
		<tr>
			<td>10:30 AM-11:00 AM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>11:00 AM-12:30 PM</td>
			<td>Tile server<br>
				<i>static vs. dynamic serving</i>
			</td>
		</tr>
		<tr>
			<td>12:30 PM-02:00 PM</td>
			<td><i>lunch</i></td>
		</tr>
		<tr>
			<td>02:00 PM-03:30 PM</td>
			<td>Data storage<br>
				<i>Choosing the correct storage method: relational databases, key-value stores, flat files, etc.</i>
			</td>
		</tr>
		<tr>
			<td>03:30 PM-04:00 PM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>04:00 PM-05:30 PM</td>
			<td>Legal considerations and hurdles of data<br>
				<i>How to not get in trouble</i>
			</td>
		</tr>
	</tbody>
</table>

### Day 4: Mapping App

<table width="100%">
	<thead>
		<tr>
			<th width="30%">Time</th>
			<th>Activity</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>09:00 AM-10:30 AM</td>
			<td>Filtering and querying data<br>
				<i>Making sense of data</i>
			</td>
		</tr>
		<tr>
			<td>10:30 AM-11:00 AM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>11:00 AM-12:30 PM</td>
			<td>Building a web map<br>
				<i>A "hello world" web map, three ways</i>
			</td>
		</tr>
		<tr>
			<td>12:30 PM-02:00 PM</td>
			<td><i>lunch</i></td>
		</tr>
		<tr>
			<td>02:00 PM-03:30 PM</td>
			<td>Creating APIs<br>
				<i>Why you don't always want to use static files</i>
			</td>
		</tr>
		<tr>
			<td>03:30 PM-04:00 PM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>04:00 PM-05:30 PM</td>
			<td>Retooling the web app to work with APIs<br>
				<i>The basics of AJAX</i>
			</td>
		</tr>
	</tbody>
</table>

### Day 5: Mapping App

<table width="100%">
	<thead>
		<tr>
			<th width="30%">Time</th>
			<th>Activity</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>09:00 AM-10:30 AM</td>
			<td>Building a mapping application<br>
				<i>Using open source web technologies to create a responsive web application.</i>
			</td>
		</tr>
		<tr>
			<td>10:30 AM-11:00 AM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>11:00 AM-12:30 PM</td>
			<td>Building a mapping app… <i>contd.</i></td>
		</tr>
		<tr>
			<td>12:30 PM-02:00 PM</td>
			<td><i>lunch</i></td>
		</tr>
		<tr>
			<td>02:00 PM-03:30 PM</td>
			<td>Building a mapping app… <i>contd.</i></td>
		</tr>
		<tr>
			<td>03:30 PM-04:00 PM</td>
			<td><i>break</i></td>
		</tr>
		<tr>
			<td>04:00 PM-05:30 PM</td>
			<td>URIs matter<br>
				<i>bookmark, give credit, cite, return, all of these are possible only because of the URI</i>
			</td>
		</tr>
	</tbody>
</table>
