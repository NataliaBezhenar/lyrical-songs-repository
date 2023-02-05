# Lyrical-GraphQL

Starter project from a GraphQL course on Udemy.com

query example:
{
songs {
title
id
}
}

mutation example:
mutation AddSong($title: String) {
addSong(title: $title){
id
title
}
}
