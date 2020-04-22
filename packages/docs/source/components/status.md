# Status

The Status component is used to indicate the state of a system, process, or item.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <span class="ods-status is-ods-status-neutral">Neutral</span>
    <span class="ods-status is-ods-status-success">Success</span>
    <span class="ods-status is-ods-status-caution">Caution</span>
    <span class="ods-status is-ods-status-danger">Danger</span>
  </div>
</figure>

## Usage

- Supporting label (pull from Figma)
- Statuses per page/item/view

### Labeled

- build .ods-status-label

### Unlabaled

## Variants

The semantic states, colors they're associated with, and example use cases are as follows:

### Neutral

Neutral Statuses are gray and should be used to indicate states like Paused, Not Started, or Queued.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <span class="ods-status is-ods-status-neutral">Service paused</span>
  </div>

  ```html
  <span class="ods-status is-ods-status-neutral">Service paused</span>
  ```
</figure>

### Success

Success Statuses are green and should be used to indicate states like Complete, Active, Available, New, Service Operational.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <span class="ods-status is-ods-status-success">Service operational</span>
  </div>

  ```html
  <span class="ods-status is-ods-status-success">Service operational</span>
  ```
</figure>

### Caution

Caution Statuses are yellow and should be used to indicate states like Attention Suggested or Service Degradation.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <span class="ods-status is-ods-status-caution">Service degradation</span>
  </div>

  ```html
  <span class="ods-status is-ods-status-caution">Service degradation</span>
  ```
</figure>

### Danger

Danger Statuses are red and should be used to indicate states like Error, Failure, or Service Disruption.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <span class="ods-status is-ods-status-danger">Service disruption</span>
  </div>

  ```html
  <span class="ods-status is-ods-status-danger">Service disruption</span>
  ```
</figure>

## Content guidelines

- word count
- capitalization
- description of state

## Accessibility

If the current state of Status may change asynchronously while a user is visiting the page, utilize the `role="status"` attribute to ensure that assistive technologies correctly indicate this change.

<strong>Note:</strong> This attribute must be present <em>before</em> the change occurs.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <span class="ods-status is-ods-status-success" role="status">System operational (for now)</span>
  </div>

  ```html
  <span class="ods-status is-ods-status-success" role="status">System operational (for now)</span>
  ```
</figure>
