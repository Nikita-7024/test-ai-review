# test-ai-review
function getUserData(userId) {
  var data = db.query("SELECT * FROM users WHERE id = " + userId)
  var email = data.email
  console.log("User email: " + email)
  return data
}
