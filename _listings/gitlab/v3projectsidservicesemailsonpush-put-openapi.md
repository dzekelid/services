---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Put Projects Services Emails On Push
  version: 1.0.0
  description: Set emails-on-push service for project
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/projects/{id}/services/asana:
    put:
      summary: Put Projects Services Asana
      description: Set asana service for project
      operationId: putV3ProjectsIdServicesAsana
      x-api-path-slug: v3projectsidservicesasana-put
      parameters:
      - in: formData
        name: api_key
        description: User API token
      - in: path
        name: id
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: restrict_to_branch
        description: Comma-separated list of branches which will be automatically
          inspected
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Asana
  /v3/projects/{id}/services/assembla:
    put:
      summary: Put Projects Services Assembla
      description: Set assembla service for project
      operationId: putV3ProjectsIdServicesAssembla
      x-api-path-slug: v3projectsidservicesassembla-put
      parameters:
      - in: path
        name: id
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: subdomain
        description: Subdomain setting
      - in: formData
        name: token
        description: The authentication token
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Assembla
  /v3/projects/{id}/services/bamboo:
    put:
      summary: Put Projects Services Bamboo
      description: Set bamboo service for project
      operationId: putV3ProjectsIdServicesBamboo
      x-api-path-slug: v3projectsidservicesbamboo-put
      parameters:
      - in: formData
        name: bamboo_url
        description: Bamboo root URL like https://bamboo
      - in: formData
        name: build_key
        description: Bamboo build plan key like
      - in: path
        name: id
      - in: formData
        name: password
        description: Passord of the user
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: username
        description: A user with API access, if applicable
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Bamboo
  /v3/projects/{id}/services/bugzilla:
    put:
      summary: Put Projects Services Bugzilla
      description: Set bugzilla service for project
      operationId: putV3ProjectsIdServicesBugzilla
      x-api-path-slug: v3projectsidservicesbugzilla-put
      parameters:
      - in: formData
        name: description
        description: Description
      - in: path
        name: id
      - in: formData
        name: issues_url
        description: Issues URL
      - in: formData
        name: new_issue_url
        description: New issue URL
      - in: formData
        name: project_url
        description: Project URL
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: title
        description: Title
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Bugzilla
  /v3/projects/{id}/services/buildkite:
    put:
      summary: Put Projects Services Buildkite
      description: Set buildkite service for project
      operationId: putV3ProjectsIdServicesBuildkite
      x-api-path-slug: v3projectsidservicesbuildkite-put
      parameters:
      - in: formData
        name: enable_ssl_verification
        description: Enable SSL verification for communication
      - in: path
        name: id
      - in: formData
        name: project_url
        description: The buildkite project URL
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: token
        description: Buildkite project GitLab token
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Buildkite
  /v3/projects/{id}/services/builds-email:
    put:
      summary: Put Projects Services Builds Email
      description: Set builds-email service for project
      operationId: putV3ProjectsIdServicesBuildsEmail
      x-api-path-slug: v3projectsidservicesbuildsemail-put
      parameters:
      - in: formData
        name: add_pusher
        description: Add pusher to recipients list
      - in: formData
        name: build_events
        description: Event will be triggered when a build status changes
      - in: path
        name: id
      - in: formData
        name: notify_only_broken_builds
        description: Notify only broken builds
      - in: formData
        name: recipients
        description: Comma-separated list of recipient email addresses
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Builds
      - Email
  /v3/projects/{id}/services/campfire:
    put:
      summary: Put Projects Services Campfire
      description: Set campfire service for project
      operationId: putV3ProjectsIdServicesCampfire
      x-api-path-slug: v3projectsidservicescampfire-put
      parameters:
      - in: path
        name: id
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: room
        description: Campfire room
      - in: formData
        name: subdomain
        description: Campfire subdomain
      - in: formData
        name: token
        description: Campfire token
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Campfire
  /v3/projects/{id}/services/custom-issue-tracker:
    put:
      summary: Put Projects Services Custom Issue Tracker
      description: Set custom-issue-tracker service for project
      operationId: putV3ProjectsIdServicesCustomIssueTracker
      x-api-path-slug: v3projectsidservicescustomissuetracker-put
      parameters:
      - in: formData
        name: description
        description: Description
      - in: path
        name: id
      - in: formData
        name: issues_url
        description: Issues URL
      - in: formData
        name: new_issue_url
        description: New issue URL
      - in: formData
        name: project_url
        description: Project URL
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: title
        description: Title
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Custom
      - Issue
      - Tracker
  /v3/projects/{id}/services/drone-ci:
    put:
      summary: Put Projects Services Drone Ci
      description: Set drone-ci service for project
      operationId: putV3ProjectsIdServicesDroneCi
      x-api-path-slug: v3projectsidservicesdroneci-put
      parameters:
      - in: formData
        name: drone_url
        description: Drone CI URL
      - in: formData
        name: enable_ssl_verification
        description: Enable SSL verification for communication
      - in: path
        name: id
      - in: formData
        name: merge_request_events
        description: Event will be triggered when a merge request is created/updated/merged
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: tag_push_events
        description: Event will be triggered when a new tag is pushed to the repository
      - in: formData
        name: token
        description: Drone CI token
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Drone
      - Ci
  /v3/projects/{id}/services/emails-on-push:
    put:
      summary: Put Projects Services Emails On Push
      description: Set emails-on-push service for project
      operationId: putV3ProjectsIdServicesEmailsOnPush
      x-api-path-slug: v3projectsidservicesemailsonpush-put
      parameters:
      - in: formData
        name: disable_diffs
        description: Disable code diffs
      - in: path
        name: id
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: recipients
        description: Comma-separated list of recipient email addresses
      - in: formData
        name: send_from_committer_email
        description: Send from committer
      - in: formData
        name: tag_push_events
        description: Event will be triggered when a new tag is pushed to the repository
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Emails
      - "On"
      - Push
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---