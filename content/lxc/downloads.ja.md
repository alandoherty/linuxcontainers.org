![Download icon](/static/img/download.png)
# ディストリビューションでのインストール <!-- Distribution packages -->

<!--
LXC is included in most Linux distributions.
In most cases installing it is as simple as selecting it in your package manager.
-->
LXC は大部分の Linux ディストリビューションに含まれています。
インストールする場合は、ディストリビューションのパッケージマネージャで LXC を選択するのが簡単でしょう。

<!--
Distributions also often provide backports of newer versions of LXC for their stable releases.
You may want to look for that, especially if your distribution doesn't include LXC 1.0.
-->
ディストリビューションでは、ディストリビューションの stable リリースに対する LXC のより新しいバージョンのバックポートが提供されるケースも多いでしょう。
LXC 1.0 がディストリビューションの stable リリースに含まれない場合は特に、それを使うことも選択肢の一つでしょう。

<!--
For production environment, try to stick to LXC 1.0.x as this is the long term,
stable release which we will support until April 2019.
-->
Production 環境では、2019 年 4 月までの長期サポートの Stable リリースである LXC 1.0.x を使い続けることをお勧めします。

<!--
For Ubuntu users, we have official PPAs for LXC:
-->
Ubuntu ユーザは、LXC のオフィシャルな PPA があります:

 * [lxc-lts](https://launchpad.net/~ubuntu-lxc/+archive/lxc-lts): 最新の長期サポート版リリース <!-- Latest long term release -->
 * [lxc-stable](https://launchpad.net/~ubuntu-lxc/+archive/lxc-stable): 最新の stable リリース <!-- Latest stable release -->

<!--
And for those who want development snapshots:
-->
開発中のスナップショットが必要な場合はこちらです:

 * [lxc-git-master](https://launchpad.net/~ubuntu-lxc/+archive/lxc-git-master): "master" ブランチ <!-- "master" branch -->
 * [lxc-git-stable-1.0](https://launchpad.net/~ubuntu-lxc/+archive/lxc-git-stable-1.0): "stable-1.0" ブランチ <!-- "stable-1.0" branch -->
 * [lxc-git-stable-1.1](https://launchpad.net/~ubuntu-lxc/+archive/lxc-git-stable-1.1): "stable-1.1" ブランチ <!-- "stable-1.1" branch -->

# 現時点の開発バージョン <!-- Current development version -->

<!--
LXC has two active git branches:
-->
LXC にはアクティブな git ブランチが 2 つ存在します:

 * **master**: 現在の開発ブランチ <!-- Current development branch -->
 * **stable-1.0**: LXC 1.0.x 向けの Stable の更新用ブランチ <!-- Stable update branch for LXC 1.0.x -->

<!--
You can clone those directly with:
-->
以下から直接 clone できます:

    git clone git://github.com/lxc/lxc -b <branch name>

# リリース版 tarball <!-- Release tarballs -->

<!--
Stable release tarballs are available for download below.
All the post 1.0 ones are GPG signed by one of the maintainers.
-->
Stable リリース版の tarball は以下から取得できます。
1.0 の過去のリリースは全てメンテナの GPG による署名が行われています。
