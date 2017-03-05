# alfred-nodejs-tools

This Alfred 3 Workflow includes some useful tools for node.js developers:

- `node ls`: List NPM top-level packages. List packages for current default node.js installation (regardless of whether is managed by NVM or not).
- `node nvm ls`: List all NVM installations top-level packages. List top-level packages for all node.js installations managed by NVM.
- `node nvm install (new-version) (old-version)`: Install a new node.js using NVM. You optionally can select an old version to reinstall packages to new version, or use `none` to skip this part. The list of available versions is automatically pulled from [https://nodejs.org/dist/](https://nodejs.org/dist/).

# License

This workflow is licensed under Apache License 2.0. See [LICENSE](LICENSE) for more details.

```
Copyright 2017 Xavier Rubio Jansana

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

   [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

