<img height="128px" width="128px" align="right" />

# DVR-Request-info


> Surveillance Camera installation fillup form

<table>
	<thead>
		<tr>
			<th align="center"><strong>Contents</strong></th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
				<ol>
					<li><a href="#getting-started">Getting Started</a></li>
					<ol>
						<li><a href="#prerequisites">Prerequisites</a></li>
						<li><a href="#installation">Installation</a></li>
						<li><a href="#usage">Usage</a></li>
					</ol>
					<li><a href="#architecture">Architecture</a></li>
					<li><a href="#dependencies">Dependencies</a></li>
					<li><a href="#license">License</a></li>
				</ol>
			</td>
		</tr>
	</tbody>
</table>

### Getting Started

#### Prerequisites

- [Node.js](https://nodejs.org/en/download/)

#### Installation

```bash
git clone https://github.com/uplinks/DVR-Request-info.git
cd DVR-Request-info
npm install
```

#### Usage

```bash
npm start
```

### Architecture
        * How many Cameras needed ?
        * What type of Cameras? (Dome/Bullets/PTZ)
        * DVR or NVR?
        * How many channels?
        * What type of wiring? (Cat5e or RG59)
        * Average run length?
        * Storage Size?  (4TB, 6TB, 12TB, Others)
        * Storage Type?  (HD only, HD + Cloud)
        * Any special materials needed? (ex. Conduits, Lock box)

        Once the form is filled I should recieve an e-mail with the info.





### Dependencies

### License

`DVR-Request-info` is licensed under the [MIT License](https://github.com/uplinks/DVR-Request-info/blob/master/LICENSE).

All files located in the `node_modules` directory are externally maintained libraries used by this software which have their own licenses; it is recommend that you read them, as their terms may differ from the terms in the MIT License.