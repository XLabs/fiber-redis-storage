# fiber-redis-storage

Improved redis storage module for fiber based on https://github.com/gofiber/storage/tree/main/redis
- Error handling on caller side (no panic internally)
- Support for key prefix (allow to group keys)
