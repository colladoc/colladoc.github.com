---
title: Home
layout: default
---

Introduction
============

**Ease the contribution of Scala documentation by leveraging the means of social collaboration.**

Goal of this project is to explore the possibility of using social
collaboration for development of Scala project documentation. There are many
developers using Scala that would like to collaborate on Scala platform in
order to make it better, but does not have enough knowledge or enthusiasm to
directly contribute to the development of Scala compiler and related tools.
The Colladoc application should allow them to easily contribute by improving
Scala documentation.

Applications
============

Colladoc
--------

**Web application allowing to edit Scala symbols documentation.**

This application is based on existing Scaladoc 2 sources converted into full
featured web application using the Lift web framework. The application
internally uses the documentation model constructed using Scala compiler
frontend in the same way as Scaladoc 2 does.

The interface of this web application is extended in order to allow wiki-like
editing of Scala symbol comments. Application also allows to show different
versions of documentation related to single symbol for each users together
with displaying history of all changes in the form of aggregated timeline.

The Colladoc web application also provides REST interface which provide access
to the collected comments. This allows to export the changes and merge them
into original source code.

Mergedoc
--------

**Application allowing to merge changes into the source-code.**

Mergedoc application is a command-line tool reimplementing the functionality
of scaladoc-merge tool providing same features. Moreover, new features, such
as more direct integration with Colladoc or integration with other tools and
integrated development environments, are planned for the near future.

The application allows to merge changes exported from the Colladoc web
application to directly to source codes.

Supporters
==========

### Google

Google supported development of the project as a part of Google Summer of Code
2010 programme and basically enabled its creation. Without Google, there will
not be any Collaborative Scaladoc project.

<a href="http://code.google.com/soc/"><img src="http://code.google.com/images/2010soclogo.jpg" width="150" height="134" alt="Google Summer of Code 2010"></a>

### JetBrains

JetBrains provided free open-source license of IntelliJ IDEA for the project.
This excelent IDE is used for the development of both applications. Without
this support, the development would be much harder.

<a href="http://www.jetbrains.com/idea/" style="position: relative;display:block; width:127px; height:37px; border:0; margin:0;padding:0;text-decoration:none;text-indent:0;"><span style="margin: 0;padding: 0;position: absolute;top: 0;left: 33px;font-size: 10px;cursor:pointer;  background-image:none;border:0;color: #0d3a9e; font-family: trebuchet ms,arial,sans-serif;font-weight: normal;text-align:left;">Developed with</span><img src="http://www.jetbrains.com/idea/opensource/img/all/banners/idea125x37_white.gif" alt="The best Java IDE" border="0"/></a>

Contributing
============

Would you like to help this project? We are looking for developers which would
like to actively participate in the further development for Colladoc.
