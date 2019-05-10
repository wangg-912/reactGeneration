# react-generation

依赖于 [Ant Design Pro](https://pro.ant.design/).

Non-opinionated React Admin System integrated with decentralized composable features.

## Features

- :globe_with_meridians: **Internationalization**: [react-intl-context](https://github.com/AlanWei/react-intl-context)
- :lock: **Access control list**: [react-acl-router](https://github.com/AlanWei/react-acl-router)
- :memo: **Nested menu**: [react-sider](https://github.com/AlanWei/react-sider)

## Usage

```bash
$ git clone https://github.com/wg-paddme/reactGeneration
$ cd reactGeneration
$ npm run install
$ npm run mock:server    # start mock data server at http://localhost:3000, npm run mock:server also works
$ npm run dev            # start webpack-dev-server in another terminal window at http://localhost:8181, npm run dev also works
```

## Other

Support SCSS, less style precompiled language.

## Login Credentials

- Admin: username `admin` & password `123`, authorities is `'admin'`
- User: username `user` & password `123`, authorities is `'user'`
