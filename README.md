# mwget
- Source: https://sourceforge.net/projects/kmphpfm/.
- Anthor info: xiaosuo &lt;xiaosuo@gmail.com> &lt;xiaosuo@mail.nankai.edu.cn>
- Multi-thread wget. MWget is a "MultiLine" wget for all POSTX System!
- **Install**
  ```sh
  chmod a+x configure
  ./configure && make && make install
  ```
  For issue `configure: error: cannot guess build type; you must specify one`, folow [How to resolve configure guessing build type failure?](https://stackoverflow.com/questions/4810996/how-to-resolve-configure-guessing-build-type-failure)
  ```sh
  cp /usr/share/automake.{version}/config.guess ./
  ```
- **Usage**
  ```sh
  # -n specific num downloading threads
  mwget -n 20 http://xxxx
  ```
