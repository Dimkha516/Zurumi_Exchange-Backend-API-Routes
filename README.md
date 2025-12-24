📝 Notes for Postman Setup
Environment Variables: Create a Postman environment with:
base_url: Your API base URL (e.g., http://localhost:8000 or https://api.zurumi.com)
token: Bearer token for authenticated requests (set after login)
Authorization: For authenticated endpoints, use:
Type: Bearer Token
Token: {{token}}
Headers: Common headers for most requests:
Content-Type: application/json
Accept: application/json
Rate Limits: Pay attention to the rate limits mentioned for each module
Path Parameters: Replace {chatId}, {sessionId}, {id} with actual values when testing
File Uploads: For upload endpoints (front-upload, back-upload, etc.), change Content-Type to multipart/form-data
This organization should make it easy to navigate and test all your API endpoints in Postman!
