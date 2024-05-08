node
{
  stage('build')
  {
   if(env.Tag_Name != NULL)
   {
     echo "we are building a tag"
   }
   else
   {
     echo "we are building a branch"
   }
  if(env.Tag_Name == 'release-1.0')
  {
    echo "we are building specifically build tag"
  }
  }

}
