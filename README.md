# iacbashlinting

podman build -t script-linter .

podman run --rm -v /home/user2/code/iacbashlinting/your_script.sh:/script.sh script-linter /script.sh



