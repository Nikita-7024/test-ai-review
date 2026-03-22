# test-ai-review
function getUserData(userId) {
  var data = db.query("SELECT * FROM users WHERE id = " + userId)
  var address = data.address
  console.log("User address: " + address)
  return data
}
