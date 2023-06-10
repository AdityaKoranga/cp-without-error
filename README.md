# cp-without-error

```bash
mkdir new_directory && find . -maxdepth 1 ! -name . ! -name new_directory -exec cp -r {} ./new_directory/ \;
```
