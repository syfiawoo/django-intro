from django.db import models

# Create your models here.
from django.db import models
class Notes(models.Model):
    title= models.CharField(max_length=255)
    author= models.CharField(max_length=255)
    content = models.TextField()
    '''
    #automatically add timestamps when object is created 
    added_at = models.DateTimeField(auto_now_add=True) 
    #automatically add timestamps when object is updated
    last_update = models.DateTimeField(auto_now=True) # '''
    def __unicode__(self):
        return self.title 

