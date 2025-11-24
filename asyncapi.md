# Account Service 1.0.0 documentation

Manages user accounts in the system.

## Table of Contents

* [Servers](#servers)
* [Channels](#channels)

<a name="servers"></a>

## Servers

<table>
  <thead>
    <tr>
      <th>URL</th>
      <th>Protocol</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
  <tr>
      <td>mqtt://test.mosquitto.org</td>
      <td>mqtt</td>
      <td>Test MQTT broker</td>
    </tr>
    <tr>
      <td colspan="3">
        <details>
          <summary>URL Variables</summary>
          <table>
            <thead>
              <tr>
                <th>Name</th>
                <th>Default value</th>
                <th>Possible values</th>
                <th>Description</th>
              </tr>
            </thead>
            <tbody>
              </tbody>
          </table>
        </details>
      </td>
    </tr>
    </tbody>
</table>




## Channels



<a name="channel-user/signedup"></a>


#### Channel Parameters




###  `subscribe` user/signedup

Notify about new user registrations

#### Message


Inform about a new user registration in the system



##### Payload


<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>Description</th>
      <th>Accepted values</th>
    </tr>
  </thead>
  <tbody>

<tr>
  <td>firstName </td>
  <td>string</td>
  <td><p>foo</p>
 </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>lastName </td>
  <td>string</td>
  <td><p>bar</p>
 </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>email </td>
  <td>string</td>
  <td><p>baz</p>
 </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>createdAt </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr></tbody>
</table>


###### Example of payload _(generated)_

```json
{
  "firstName": "string",
  "lastName": "string",
  "email": "user@example.com",
  "createdAt": "2019-08-24T14:15:22Z"
}
```





