# Data toolbox app

Data toolbox provides a web interface to visualize and manipulate your Enonic XP data.

The admin tool contained allows you to:

- Browse and manage your <b>repositories</b>, branches and nodes.
- Record the state of your indexes at specific times. Rollback to these <b>snapshots</b> when needed.
- Manage your <b>node exports</b>.
- Generate and manage your <b>system dumps</b>.
- <b>Search</b> for nodes using the Enonic query language.

The Content Studio widget allows you to:

- Generate and manage your <b>content exports</b>.

Starting from version 2.0.0, help dialogs are present to give you more information about each functionality.

## Releases and Compatibility

| App version | Required XP version | Download                                                                                                                      | SHA256                                                           |
|-------------|---------------------|-------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| 5.1.6       | 7.8.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.1.5/datatoolbox-5.1.6.jar)   | 7fd56e48db110cf0a2f9d774326d1a30f42d567bce6f4f22cafe88487fa809f0 |
| 5.1.5       | 7.8.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.1.5/datatoolbox-5.1.5.jar)   | 3ced12336bf880f5323db4a781afd00f4c452ed97a1db17545da1f75e01123cf |
| 5.1.4       | 7.8.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.1.4/datatoolbox-5.1.4.jar)   | 64bf10d93bef60c726d476ffb568e1d1ddab2cc2217ad45c74ec181b85455149 |
| 5.1.3       | 7.8.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.1.3/datatoolbox-5.1.3.jar)   | 5167ba65f79f1152e887cc843c7a7649850ffb7826eef98bafbe8c0d4a95027d |
| 5.1.2       | 7.8.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.1.2/datatoolbox-5.1.2.jar)   | 83df77a00a6cf51630cf906b920d63d232c8bb2af1b8ca1fd8a9880de6c4aed9 |
| 5.1.1       | 7.8.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.1.1/datatoolbox-5.1.1.jar)   | 38ff63a808a4d3278a578a15c7071af1741fea9d59fc1bdd8c15cab4599dfb8d |
| 5.1.0       | 7.8.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.1.0/datatoolbox-5.1.0.jar)   | 3d7f42947013a1292235a49b17653cbbf064e33b19dc0436adc26ebeeec939fe |
| 5.0.31      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.31/datatoolbox-5.0.31.jar) | 4a36cb9939a58b79df69d3235e3138c87fb4eaa11498052fb71cbd8fda0cb2ee |
| 5.0.30      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.30/datatoolbox-5.0.30.jar) | 67d497fda26d001df0d491dc644e5c3d05f44bcdf9b0c53b667a311231982b4c |
| 5.0.29      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.29/datatoolbox-5.0.29.jar) | a53637fb40578077b6b3c9cffb2f73bd195040e310385f62857d7e121d849808 |
| 5.0.28      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.28/datatoolbox-5.0.28.jar) | aa1cc1559ae0d8640aa4abe970de36666ac322cc081a444f3ad8c0db216760d9 |
| 5.0.27      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.27/datatoolbox-5.0.27.jar) | 19f2ca721a6d2feae658862cfd3543349b66bcd68768f857b9ff2e622e2b7cad |
| 5.0.26      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.26/datatoolbox-5.0.26.jar) | 1a6e65e034d45fb7d84fc4b4eded1b1ecf95f6d26d5be1c1b3c4255f35bbc861 |
| 5.0.25      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.25/datatoolbox-5.0.25.jar) | 4f1c3ef7f90f540e090623cce4664df7ef048e031516aa4bfa32f22da401fe85 |
| 5.0.24      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.24/datatoolbox-5.0.24.jar) | 182baade546322e68ccc5094bbbf4d2243880f35bb0912b888f6b45a695afc7e |
| 5.0.23      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.23/datatoolbox-5.0.23.jar) | 876e68165f1816cfb312689d6e17fbb461d855135217edb0934d46bf47c7ecde |
| 5.0.22      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.22/datatoolbox-5.0.22.jar) | 1ff54c61c6598bee68f8dcfe3f19f2dbfed81346f54173d1e4eca7aa72782839 |
| 5.0.21      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.21/datatoolbox-5.0.21.jar) | fa98d0529c3631be261a20709e3247b0f4bdb4a6b9a687c5e5fa143010914675 |
| 5.0.20      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.20/datatoolbox-5.0.20.jar) | 4eb964015f5a418eab24a7fa883d09dbe0227c44916fc6c71d4a769312556884 |
| 5.0.19      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.19/datatoolbox-5.0.19.jar) | acce45ec5b5386f63e608467d9dc21929163c5eb1fec5cc63208f4861e979110 |
| 5.0.18      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.18/datatoolbox-5.0.18.jar) | 1752eb2a07432d856317f076ee06b38ca0c687756a04efe4e465871547b0d741 |
| 5.0.17      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.17/datatoolbox-5.0.17.jar) | 0e485576d1c67420c5604d52eb5e9a245dfae72c155cc0dbce81531ddc135f4f |
| 5.0.16      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.16/datatoolbox-5.0.16.jar) | b7dc67d410ea94b103943daac93de50b67cc0ca35e574269bb8a586e9d107ff0 |
| 5.0.15      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.15/datatoolbox-5.0.15.jar) | cddbf134dc72c5aff17a45267bb21a0c154612cf75c583f7f8eab06221f6bafd |
| 5.0.14      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.14/datatoolbox-5.0.14.jar) | fdd8ce5c5fb1e9eda7dd925125f21fc5efff724b11913fc5e79968aa1305ddd4 |
| 5.0.13      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.13/datatoolbox-5.0.13.jar) | e08e909c69fd4b7c8af2971accc00fd1448beb1629a7fd7a44fb8ce863d75e45 |
| 5.0.12      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.12/datatoolbox-5.0.12.jar) | 35b6c4a814fd85de1912276d57c35d4fa568181aa813cedb6af2e5e6dd019b9e |
| 5.0.11      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.11/datatoolbox-5.0.11.jar) | 1ba675c18939c22e40e8f5c1b81ecb65818b18082b9db12dfbd0108ee2660a3c |
| 5.0.10      | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.10/datatoolbox-5.0.10.jar) | b911b0abd5ba11dff5eecfbae60fdac2eb5a5a4a9b53652c6fe3f27d65d9359f |
| 5.0.9       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.9/datatoolbox-5.0.9.jar)   | ba5446b8c85591ff4c72691bb3377fb7993a52e8836df585d9ebfdadb7e5d7f0 |
| 5.0.8       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.8/datatoolbox-5.0.8.jar)   | df8eae1640f37ca8d7ba8a97b030b983614ee286e92017ac3ccd032afe63496b |
| 5.0.7       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.7/datatoolbox-5.0.7.jar)   | 00cf173294b424127e59272af119fd14ef63f4506e4047cba7f520380d039528 |
| 5.0.6       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.6/datatoolbox-5.0.6.jar)   | e4ded49ed0dceb704aca82155cff0058e5f9ee140337d6d0a4dbf9a63fab0628 |
| 5.0.5       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.5/datatoolbox-5.0.5.jar)   | 313c67bf442125d6e933c83f235edbc077711aa58cd662c4f4b002390f36dc9e |
| 5.0.4       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.4/datatoolbox-5.0.4.jar)   | 9b541aa328fe34b524d8cb0641ff9331f106d8903ddc7030c0a4d3b06fe4261c |
| 5.0.3       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.3/datatoolbox-5.0.3.jar)   | 16a0ee1a196f48e22c4e0f316b199b87b3205b8c8eafd537082d55798f065e82 |
| 5.0.2       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.2/datatoolbox-5.0.2.jar)   | e8cb4498592f6f7ba840a57ef2cc43899bd058b0c1256d6293add0df24bedc5c |
| 5.0.1       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.1/datatoolbox-5.0.1.jar)   | a3050e445e8ffed0bcf3b8241b1782321df19256c506b3d7c06119c20a1e7c5c |
| 5.0.0       | 7.3.0 - 7.Y.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/5.0.0/datatoolbox-5.0.0.jar)   | 7f03730a24889a54fa782f90d3c88e987d5fe7844859b30fb6078db9b53869ff |
| 4.0.3       | 7.0.0 - 7.2.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/4.0.3/datatoolbox-4.0.3.jar)   | cdba93c8e5c244d5a4aa4584f977a2b616adf929eecedc487a812ad859646412 |
| 4.0.2       | 7.0.0 - 7.2.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/4.0.2/datatoolbox-4.0.2.jar)   | a4816e9450e13eeaa75a63c260f8490ab2e33eba1c34ff9cc0b268e961a574dd |
| 4.0.1       | 7.0.0 - 7.2.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/4.0.1/datatoolbox-4.0.1.jar)   | 09d373988c80f0c4a3e344f9fe733a3878b9ecfaa353204836d638f2260a40bb |
| 4.0.0       | 7.0.0 - 7.2.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/4.0.0/datatoolbox-4.0.0.jar)   | e19c54edfee4b7cc67fa3504437139a57b74cb1ba65825494efce12578321523 |
| 3.0.1       | 7.0.0 - 7.2.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/3.0.1/datatoolbox-3.0.1.jar)   | e19c54edfee4b7cc67fa3504437139a57b74cb1ba65825494efce12578321523 |
| 3.0.0       | 7.0.0 - 7.2.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/3.0.0/datatoolbox-3.0.0.jar)   | f5e43ce3a1cba3efab2f2cb55452f0dbc5e2e18e879744c659da53e8ee140077 |
| 2.2.7       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.7/datatoolbox-2.2.7.jar)   | 6431fce0b8644ca1ede265bcb54107dceba290584a52e0a48107c08a87e0f87d |
| 2.2.6       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.6/datatoolbox-2.2.6.jar)   | d679829918c231dd5044d4fcaa57a2f8d3ae9e42e37578822883eed5c080cfef |
| 2.2.5       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.5/datatoolbox-2.2.5.jar)   | c7ad9b1edd216dc2adfc8a26a1ef9f00338a8f90d9cf1d9bd14a529da7e1861c |
| 2.2.4       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.4/datatoolbox-2.2.4.jar)   | 7f756b44a2447dacca1f1e06da5ddba18cc3265f0401de164cf9e9d4368385f9 |
| 2.2.3       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.3/datatoolbox-2.2.3.jar)   | 52e4af1abc2c4bdb18afca32799d30010e8a45bfe518b4156398af2f06973db1 |
| 2.2.2       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.2/datatoolbox-2.2.2.jar)   | 864dc5922b2a5324bd355ff63b7d5b5eb0bf3472b3723f11730062770c58f9e6 |
| 2.2.1       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.1/datatoolbox-2.2.1.jar)   | fdd510e84f328dcc3ea93acf248211a1dc4a88876da1a062c255643b8e385f6b |
| 2.2.0       | 6.13.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.2.0/datatoolbox-2.2.0.jar)   | 991dd87029346c62a2eec950f5ff828653ee84e247ba8fb11fb9d3c7882d3d90 |
| 2.1.7       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.7/datatoolbox-2.1.7.jar)   | 864b0b3added46957e46b90a3317e67a0e9d959de27edcf90adbdf9f05fbf964 |
| 2.1.6       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.6/datatoolbox-2.1.6.jar)   | 27a402cd84492e35cc913eba7d75b282ef0c4a4d1c2c7761ba738ac9a7e03ad8 |
| 2.1.5       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.5/datatoolbox-2.1.5.jar)   | f99f294a11dd2902bfff96da1bb8e27fc50a3c1737c034003b6cc758234a394b |
| 2.1.4       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.4/datatoolbox-2.1.4.jar)   | 401e6b77cc9284e69ea70d8d7c4f114783953c6e9ee17ffa0f955f18d1f1aeea |
| 2.1.3       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.3/datatoolbox-2.1.3.jar)   | ce6b5e45d2b136b4533b43b20c05249c8c28e9ab639f156580912bf044ec6bb8 |
| 2.1.2       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.2/datatoolbox-2.1.2.jar)   | ec74d1c147dc49f7cf965cd7a3586adf3f6d2fcda7865b5fafa56d681c99922b |
| 2.1.1       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.1/datatoolbox-2.1.1.jar)   | 77fe28ce192c353bbb229d0b1607899a81403a9744b1af9b191cf10d33d12939 |
| 2.1.0       | 6.11.0 - 6.Y.Z      | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.1.0/datatoolbox-2.1.0.jar)   | bda552e6e5c082c296d60cf36b3ac3385f0bc5d64e91ed3275943d015a4fab87 |
| 2.0.1       | 6.10.0 - 6.10.Z     | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.0.1/datatoolbox-2.0.1.jar)   | 57060d0e2bf00f4df32886b27180737e0b1690a936c76638a495e02fb99a0ca1 |
| 2.0.0       | 6.10.0 - 6.10.Z     | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/2.0.0/datatoolbox-2.0.0.jar)   | b840c11ae0c40774575a0d898097c7681dfd37e277e3a92ebd74765f7887bd8c |
| 1.2.0       | 6.10.0 - 6.10.Z     | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.2.0/datatoolbox-1.2.0.jar)   | ba04bd8751ae42a82ca85bad72c5fd6abb85310e905e6d8dc7e4d0069025e6a9 |
| 1.1.1       | 6.9.0 - 6.9.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.1.1/datatoolbox-1.1.1.jar)   | 5486122d49afa76086a8e5bae2302105919b40205e6ce192cc7119d7efc935b6 |
| 1.1.0       | 6.9.0 - 6.9.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.1.0/datatoolbox-1.1.0.jar)   | ff8ff8fcdffb423cecc18c86bc1bb8734f475a25b0f77bcb604d65a43db8a53e |
| 1.0.6       | 6.7.3 - 6.9.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.0.6/datatoolbox-1.0.6.jar)   | 07db4c753d1d43fdbf44cac908ff2dda311a3b9cc81e645c166592b2a0b2ec39 |
| 1.0.5       | 6.7.3 - 6.9.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.0.5/datatoolbox-1.0.5.jar)   | e852ee19bc80e732b54e2078682822fa56f2d7baa88a97aa29a3878e45976153 |
| 1.0.4       | 6.7.3 - 6.8.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.0.4/datatoolbox-1.0.4.jar)   | 96985ab14ebde798df23d8114c2ea5c9cdb643c6f124890bb3871e040736a2f7 |
| 1.0.3       | 6.7.3 - 6.8.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.0.3/datatoolbox-1.0.3.jar)   | 47a9f4ddd66f9ab6c356b251c8d7dcdb44b2e9034b6e1218fd3846046ca1a374 |
| 1.0.2       | 6.7.3 - 6.8.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.0.2/datatoolbox-1.0.2.jar)   | ad80ff8cac5db114bb3355bcb144a82c64a2ac302e896169d7065757c450ee8c |
| 1.0.1       | 6.7.3 - 6.8.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.0.1/datatoolbox-1.0.1.jar)   | 6d197b61b4471ee0aa5b58d3e711e2aadc62f6117c32c487642f4f5f56e57f61 |
| 1.0.0       | 6.7.3 - 6.8.Z       | [Download](https://github.com/GlennRicaud/maven/raw/main/systems/rcd/enonic/datatoolbox/1.0.0/datatoolbox-1.0.0.jar)   | 2108e9213accd03fa67e5f0b06e905484209903831d9f4485ca5d27d3651e6d6 |

## Changelog

- 5.1.6 (Mar 3rd 2025)
    - Bug: Fix DOM text handling
    - Compatibility:7.8.0
- 5.1.5 (Nov 9th 2024)
    - Adaptation: Change config attribute name (Required by Content Studio 6)
    - Compatibility:7.8.0
- 5.1.4 (Jun 2nd 2024)
    - Enhancement: Additional log on node retrieval failure
    - Compatibility:7.8.0
- 5.1.3 (Apr 23rd 2024)
    - Enhancement: Warning dialog on dump load and snapshot restore
    - Compatibility:7.8.0
- 5.1.2 (Mar 29th 2024)
    - Bug: Scrollable navigation drawer
    - Adaptation: Versions view: Remove "Set active in..." option (Required by Enonic XP 8)
    - Enhancement: Content View (Beta): Display as JSON, Delete, Help dialogs
    - Compatibility:7.8.0
- 5.1.1 (Jan 19th 2024)
    - Enhancement: Search Report: Node fields as TSV (Allow nested field)
    - Compatibility:7.8.0
- 5.1.0 (Jan 8th 2024)
    - Enhancement: Content View (Beta 1)
    - Enhancement: Restore archived content
    - Compatibility:7.8.0
- 5.0.31 (Dec 27th 2023)
    - Enhancement: Progress on upload
    - Compatibility:7.3.0
- 5.0.30 (Dec 22nd 2023)
    - Enhancement: Feedback on archiving/unarchiving
    - Compatibility:7.3.0
- 5.0.29 (Dec 3rd 2023)
    - Enhancement: Display used/usable space on node export
    - Compatibility:7.3.0
- 5.0.28 (Aug 21st 2023)
    - Bug: Support unicode characters in JSON view
    - Compatibility:7.3.0
- 5.0.27 (Aug 21st 2023)
    - Adaptation: Remove Nashorn API usage (Required by Enonic XP 7.13 / Java 17)
    - Compatibility:7.3.0
- 5.0.26 (Apr 6th 2023)
    - Enhancement: XP Home view
    - Enhancement: Display used/usable space on dump/export creation
    - Compatibility:7.3.0
- 5.0.25 (Nov 6th 2022)
    - Bug: Node Search: Keep filters through pagination
    - Bug: Data Tree: Nodes: Fix display issues for custom displayed fields
    - Compatibility:7.3.0
- 5.0.24 (Mar 6th 2022)
    - Adaptation: Export widget: Removed inline JS (Required by Content Studio 4.1)
    - Compatibility:7.3.0
- 5.0.23 (Mar 6th 2022)
    - Enhancement: Nodes view: Create child node
    - Compatibility:7.3.0
- 5.0.22 (Jan 31st 2022)
    - Bug: Fix JSON string escaping
    - Compatibility:7.3.0
- 5.0.21 (Dec 14th 2021)
    - Enhancement: Node Search: Report: New format: Node fields as CSV
    - Adaptation: Audit Log: Handle new runtime log types
    - Compatibility:7.3.0
- 5.0.20 (Nov 26th 2021)
    - Adaptation: Remove admin rest API dependency (Required by Enonic XP 7.8)
    - Compatibility:7.3.0
- 5.0.19 (Nov 20th 2021)
    - Bug: Handle websocket connection failure
    - Compatibility:7.3.0
- 5.0.18 (Nov 12th 2021)
    - Enhancement: Nodes view: Set displayed fields
    - Compatibility:7.3.0
- 5.0.17 (Oct 27th 2021)
    - Enhancement: Permissions view: Edit permissions
    - Compatibility:7.3.0
- 5.0.16 (Sept 12th 2021)
    - Enhancement: Analyze view
    - Compatibility:7.3.0
- 5.0.15 (July 18th 2021)
    - Refactoring: Remove Nashorn dependency
    - Refactoring: Remove non-WOFF font formats
    - Compatibility:7.3.0
- 5.0.14 (June 9th 2021)
    - Adaptation: Fix script engine access in XP 7.7
    - Compatibility:7.3.0
- 5.0.13 (May 13th 2021)
    - Enhancement: Navigability: Actions & ListRows as buttons
    - Compatibility:7.3.0
- 5.0.12 (May 9th 2021)
    - Enhancement: Navigability: Anchors in tables and view summaries
    - Compatibility:7.3.0
- 5.0.11 (Mar 31st 2021)
    - Enhancement: Node Search: Filters
    - Compatibility:7.3.0
- 5.0.10 (Feb 28th 2021)
    - Enhancement: Node View: Push node
    - Compatibility:7.3.0
- 5.0.9 (Dec 14th 2020)
    - Bug: Fix layout display for >=1600px viewport width
    - Compatibility:7.3.0
- 5.0.8 (Dec 12th 2020)
    - Enhancement: Events view
    - Compatibility:7.3.0
- 5.0.7 (Nov 27th 2020)
    - Bug: Task Manager: Keep websocket connection alive
    - Compatibility:7.3.0
- 5.0.6 (Nov 27th 2020)
    - Enhancement: Node versions: Active versions & Set active
    - Compatibility:7.3.0
- 5.0.5 (Nov 15th 2020)
    - Enhancement: Node versions: Display commit
    - Compatibility:7.3.0
- 5.0.4 (Oct 18th 2020)
    - Enhancement: Node search: Result report generation
    - Enhancement: Node search: Display score
    - Compatibility:7.3.0
- 5.0.3 (Oct 3rd 2020)
    - Documentation: Make documentation links point to Developer Portal
    - Compatibility:7.3.0
- 5.0.2 (Sep 12th 2020)
    - Enhancement: Audit Log view
    - Compatibility:7.3.0
- 5.0.1 (Sep 1st 2020)
    - Bug: Handle missing dump directory
    - Compatibility:7.3.0
- 5.0.0 (Jul 9th 2020)
    - Adaptation: Handle XP dump archives
    - Breaking change: Do not handle archive of multiple dumps (Please unzip and zip separately)
    - Compatibility:7.3.0
- 4.0.3 (Mar 1st 2020)
    - Enhancement: Tasks view
    - Enhancement: Use Event WS as default source of task state information
    - Compatibility:7.0.0
- 4.0.2 (Feb 15th 2020)
    - Bug: Fix group display
    - Compatibility:7.0.0
- 4.0.1 (Feb 15th 2020)
    - Enhancement: IAM - Iteration 1
    - Enhancement: Data Tables - Rows per page
    - Enhancement: Impove logging coverage
    - Bug: Fix node export upload
    - Compatibility:7.0.0
- 4.0.0 (Feb 13th 2020)
    - Enhancement: Replace JQuery by Fetch API
    - Refactoring: Optimized build
    - Refactoring: ECMAScript 6
    - Compatibility:7.0.0
- 3.0.1 (Jun 11th 2019)
    - Enhancement: Nav items & breadcrumbs as HTML links
    - Compatibility:7.0.0
- 3.0.0 (May 18th 2019)
    - Adaptation: Adapt to Enonic 7.0 changes
    - Enhancement: Blob display
    - Enhancement: Version view
    - Enhancement: Dump upgrade
    - Compatibility:7.0.0
- 2.2.7 (Feb 14th 2020)
    - Bug: 404 error on task retrieval
    - Compatibility:6.13.0
- 2.2.6 (Aug 6th 2019)
    - Bug: Handle 6.11/6.12 dumps
    - Compatibility:6.13.0
- 2.2.5 (May 25th 2019)
    - Adaptation: Use admin task endpoint for progress
    - Bug: Fixed widget service URL
    - Compatibility:6.13.0
- 2.2.4 (Mar 24th 2019)
    - Bug: Synchronous snapshot restore operation
    - Compatibility:6.13.0
- 2.2.3 (Sep 26th 2018)
    - Enhancement: Download binary reference
    - Enhancement: Dump without version history (Enonic XP >=6.14.0)
    - Compatibility:6.13.0
- 2.2.2 (Sep 25th 2018)
    - Enhancement: Node search: Paging and sorting
    - Enhancement: Node view: Search/Branch/Version Index Document
    - Compatibility:6.13.0
- 2.2.1 (Sep 21st 2018)
    - Enhancement: About page
    - Enhancement: Node view
    - Enhancement: Advanced search
    - Enhancement: Quick search
    - Enhancement: Follow reference
    - Compatibility:6.13.0
- 2.2.0Apr 1st 2018
    - Enhancement: Import/export progress
    - Enhancement: Dump/load progress
    - Bug: Encode/decode state parameters
    - Compatibility:6.13.0
- 2.1.7 (Mar 11th 2018)
    - Adaptation: Handle multiple displays export widget (Required by Enonic XP 6.14)
    - Compatibility:6.11.0
- 2.1.6 (Mar 11th 2018)
    - Bug: Node properties - Handle JSON/HTML special characters
    - Enhancement: Minor UI improvements (fav icon, boolean/string fields, ...)
    - Compatibility:6.11.0
- 2.1.5 (Jan 7th 2018)
    - Enhancement: Exports Widget - Specify target parent content path
    - Compatibility:6.11.0
- 2.1.4 (Dec 6th 2017)
    - Enhancement: Asynchronous requests for heavy operations
    - Enhancement: Node properties creation/edition
    - Enhancement: Rename/move node
    - Enhancement: Successful action snackbars
    - Compatibility:6.11.0
- 2.1.3 (Oct 16th 2017)
    - Enhancement: Widget listed only for system admins (Enonic XP >=6.12)
    - Enhancement: Branch name in default export names
    - Enhancement: Parent row - New first row allowing to navigate to parent node/branch
    - Enhancement: Node permissions view (Read only)
    - Enhancement: Node metadata view (Read only)
    - Enhancement: Node data view (Read only)
    - Compatibility:6.11.0
- 2.1.2 (Sep 25th 2017)
    - Enhancement: Node export report
    - Enhancement: Dump generation report
    - Enhancement: Dump load report
    - Compatibility:6.11.0
- 2.1.1 (Aug 15th 2017)
    - Bug: Exports should not include versions
    - Compatibility:6.11.0
- 2.1.0 (Jul 13th 2017)
    - Enhancement: Handle 6.11 system dumps (Required by Enonic XP 6.11)
    - Enhancement: Backward compatibility for <6.11 system dumps
    - Enhancement: Display dump versions
    - Bug: Delete branch fix
    - Compatibility:6.11.0
- 2.0.1 (Jun 16th 2017)
    - Enhancement: Node details: JSON formating and HTML escaping
    - Enhancement: Nodes view: Node sorting
    - Enhancement: Nodes view: Node filtering
    - Bug: Node/Content import report: Updated node paths are now displayed correctly
    - Compatibility:6.10.0
- 2.0.0 (May 18th 2017)
    - Enhancement: Responsiveness & stricter implementation of Material specifications
    - Enhancement: Content/Node import report
    - Enhancement: Help dialogs
    - Compatibility:6.10.0
- 1.2.0 (Mar 26th 2017)
    - Adaptation: Enonic XP 6.10 snapshot API (Required by Enonic XP 6.10)
    - Compatibility:6.10.0
- 1.1.1 (Mar 12th 2017)
    - Enhancement: Exports view
    - Enhancement: Repositories/Branches/Nodes views
    - Compatibility:6.9.0
- 1.1.0 (Jan 17th 2017)
    - Enhancement: Handle custom repositories and branches (Required by Enonic XP 6.9)
    - Compatibility:6.9.0
- 1.0.6 (Mar 12th 2017)
    - Bug: Cross-env zip usage
    - Compatibility:6.8.0
- 1.0.5 (Dec 17th 2016)
    - Bug: Modified size retrieval of temporary files (Required by Enonic XP 6.9)
    - Compatibility:6.8.0
- 1.0.4 (Nov 24th 2016)
    - Enhancement: Handle selfmade zips
    - Enhancement: Handle MAC OS X Finder zips
    - Compatibility:6.8.0
- 1.0.3 (Nov 19th 2016)
    - Enhancement: Display network & server errors
    - Compatibility:6.8.0
- 1.0.2 (Nov 14th 2016)
    - Bug: Fix doUpload method call
    - Compatibility:6.8.0
- 1.0.1 (Nov 13th 2016)
    - Enhancement: Hide widget if user is missing admin role
    - Compatibility:6.8.0
- 1.0.0 (Nov 12th 2016)
    - First release
    - Compatibility:6.8.0

## Data Toolbox semantic versioning

To allow to patch old versions, the versions of DT follow the following rules

- X: Change of major Enonic XP version OR Major refactoring
- Y: Change of minimum minor Enonic XP version
- Z: Enhancement or bugfix without change in the minimum minor Enonic XP version
