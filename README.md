paper-progress-button [![Bower version](https://badge.fury.io/bo/paper-progress-button.svg)](http://badge.fury.io/bo/paper-progress-button) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/Collaborne/paper-progress-button)
=========

A paper button gets disabled and shows a spinner while submitting

To install the element:

`bower install paper-progress-button`

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="../paper-checkbox/paper-checkbox.html">
		<link rel="import" href="../paper-styles/demo-pages.html">
    <link rel="import" href="paper-progress-button.html">
    <dom-bind>
      <template is="dom-bind">
        <next-code-block></next-code-block>
      </template>
    </dom-bind>
  </template>
</custom-element-demo>
```
-->
```html
<paper-progress-button
    active="[[active]]"
    active-text="Submit"
    inactive-text="Submitting..."
    raised>
</paper-progress-button>
<paper-checkbox checked="{{active}}">Active</paper-checkbox>
```

## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
