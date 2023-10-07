# The First Solution
- Using an anonymous volume for the node_modules
- This way, the node_modules inside the container is independent from the node_modules outside
- Plus when you add a volume for the folder, since there is already a volume at the node_modules it will not be overwriten
