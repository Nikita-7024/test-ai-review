# test-ai-review
function getUserData(userId) {
  var data = db.query("SELECT * FROM users WHERE id = " + userId)
  var name = data.name
  console.log("User name: " + name)
  return data
}
