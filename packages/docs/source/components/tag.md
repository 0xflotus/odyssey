# Tag

Tags are used to categorize or label content. They serve as descriptors or keywords that can help differentiate between different types of content in a view. They aid navigation and make parsing content more efficient.

## Usage

Tags should be used in instances where a descriptor of a content type is needed. These can be used singularly or in sets. Currently, Tags are non-interactive and cannot be used to filter or navigate.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <ul class="ods-tag--list"><li class="ods-tag">Animal</li><li class="ods-tag">Small</li><li class="ods-tag">Fuzzy</li><li class="ods-tag">Quadruped</li></ul>
  </div>

  ```html
  <ul class="ods-tag--list">
    <li class="ods-tag">Animal</li>
    <li class="ods-tag">Small</li>
    <li class="ods-tag">Fuzzy</li>
    <li class="ods-tag">Quadruped</li>
  </ul>
  ```
</figure>

## Variants

### Removable Tags

This variant includes a button that allows the Tag to be removed by a user. When using removable Tags, be sure to include an appropriate `aria-label` on the associated button.

<figure class="nimatron--example">
  <div class="nimatron--rendered">
    <ul class="ods-tag--list">
      <li class="ods-tag">Animal<button class="ods-tag--button" aria-label="Remove 'Animal' from the list of tags"></button></li>
      <li class="ods-tag">Small<button class="ods-tag--button" aria-label="Remove 'Small' from the list of tags"></button></li>
      <li class="ods-tag">Fuzzy<button class="ods-tag--button" aria-label="Remove 'Fuzzy' from the list of tags"></button></li>
      <li class="ods-tag">Quadruped<button class="ods-tag--button" aria-label="Remove 'Quadruped' from the list of tags"></button></li>
    </ul>
  </div>

  ```html
  <ul class="ods-tag--list">
    <li class="ods-tag">Animal<button class="ods-tag--button" aria-label="Remove 'Animal' from the list of tags"></button></li>
    <li class="ods-tag">Small<button class="ods-tag--button" aria-label="Remove 'Small' from the list of tags"></button></li>
    <li class="ods-tag">Fuzzy<button class="ods-tag--button" aria-label="Remove 'Fuzzy' from the list of tags"></button></li>
    <li class="ods-tag">Quadruped<button class="ods-tag--button" aria-label="Remove 'Quadruped' from the list of tags"></button></li>
  </ul>
  ```
</figure>

### Color Tags
