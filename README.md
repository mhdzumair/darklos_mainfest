# Dark Lineage platform manifest  

## Setup

- Create directory
```
mkdir darklos
cd darklos
```

- To initialize your local repository using the Dark LineageOS trees, use a command like this:
```
repo init -u https://github.com/mhdzumair/darklos_mainfest.git
```

- To syncup silently with 4 no of cpu
```
repo sync -c -j4 --force-sync --no-clone-bundle --no-tags -q
```
