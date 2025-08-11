# Public endpoint
curl.exe http://localhost:8080/api/public

# Private endpoint without token
curl.exe http://localhost:8080/api/private

# Private endpoint with token
curl.exe -H "Authorization: Bearer valid-token" http://localhost:8080/api/private
