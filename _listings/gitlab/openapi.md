swagger: "2.0"
x-collection-name: GitLab
x-complete: 1
info:
  title: API title
  version: 1.0.0
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/projects/{id}/issues/{issue_id}/time_stats:
    get:
      summary: Get Projects Issues Issue Time Stats
      description: Get projects issues issue time stats.
      operationId: getV3ProjectsIdIssuesIssueIdTimeStats
      x-api-path-slug: v3projectsidissuesissue-idtime-stats-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: path
        name: issue_id
        description: The ID of a project issue
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Time
      - Stats
  /v3/projects/{id}/merge_requests/{merge_request_id}/time_stats:
    get:
      summary: Get Projects Merge Requests Merge Request Time Stats
      description: Get projects merge requests merge request time stats.
      operationId: getV3ProjectsIdMergeRequestsMergeRequestIdTimeStats
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idtime-stats-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: path
        name: merge_request_id
        description: The ID of a project merge_request
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Time
      - Stats
  /v3/sidekiq/job_stats:
    get:
      summary: Get Sekiq Job Stats
      description: Get the Sidekiq job statistics
      operationId: getV3SidekiqJobStats
      x-api-path-slug: v3sidekiqjob-stats-get
      responses:
        200:
          description: OK
      tags:
      - Sekiq
      - Job
      - Stats