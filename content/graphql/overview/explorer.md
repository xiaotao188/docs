---
title: Explorer
redirect_from:
  - /v4/explorer
  - /v4/explorer-new
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
layout: graphql-explorer
topics:
  - API
---

{
  user: viewer {
    createdAt
    y2020: contributionsCollection(from: "2020-05-01T00:00:00Z", to: "2021-04-30T23:59:59Z") {
      endedAt
      restrictedContributionsCount
      contributionCalendar {
        totalContributions
      }
    }
    y2019: contributionsCollection(from: "2019-05-01T00:00:00Z", to: "2020-04-30T23:59:59Z") {
      endedAt
      restrictedContributionsCount
      contributionCalendar {
        totalContributions
      }
    }
    y2018: contributionsCollection(from: "2018-05-01T00:00:00Z", to: "2019-04-30T23:59:59Z") {
      endedAt
      restrictedContributionsCount
