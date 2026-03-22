function getUserData(userId) {
  var data = db.query("SELECT * FROM users WHERE id = " + userId)
  var password = data.password
  console.log("User password: " + password)
  return data
}
