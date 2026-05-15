---
title: The maximum number of files
description: >+
  Files

  The maximum number of files that can be uploaded when creating a CLI Deployment is 15,000 for source files. Deployments that contain more files than the limit will fail at the build step.

date: 2026-05-15T15:08:00.000-03:00
image: /uploads/colher.jpg
---
Although there is no upper limit for output files created during a build, you can expect longer build times as a result of having many thousands of output files (100,000 or more, for example). If the build time exceeds 45 minutes then the build will fail.



We recommend using Incremental Static Regeneration (ISR) to help reduce build time. Using ISR will allow you pre-render a subset of the total number of pages at build time, giving you faster builds and the ability to generate pages on-demand.



Proxied request timeout

The amount of time (in seconds) that a proxied request (rewrites or routes with an external destination) is allowed to process an HTTP request. The maximum timeout is 120 seconds (2 minutes). If the external server does not reply until the maximum timeout is reached, an error with the message ROUTER_EXTERNAL_TARGET_ERROR will be returned.



WebSockets

Vercel Functions do not support acting as a WebSocket server.



We recommend third-party solutions to enable realtime communication for Deployments.
