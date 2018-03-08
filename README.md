# Test
test desc
digraph flow {
  imgA -- uploadA
  imgB -- uploadB
  uploadB -- cache
  cache -- done
  uploadA -- done
}
