---
layout: post
title: "Liferay web-form portlet, customer validation"
description: "setting up and usage"
category: "liferay"
tags: ["liferay", "web form", "portlet", "javascript"]
---
{% include JB/setup %}

## issue
I set up customer validation for web form, but javascript does not run

## cause
You probably forgot to set validation.script.enabled=true in portlet.properties.

* edit portlet.properties in web-form-portlet-????.war's WEB-INF\classes dir
* redeploy the portlet

