FROM registry.access.redhat.com/ubi9/python-311

ENV LANG='en_US.UTF-8' LANGUAGE='en_US:en'


# We make four distinct layers so if there are application changes the library layers can be re-used
# Python source code
COPY --chown=185 src/python/ /app/src/              
# Python dependencies
COPY --chown=185 requirements.txt /app/      
# Jupyter notebooks
COPY --chown=185 src/notebooks/ /app/notebooks/   

EXPOSE 8000
USER 185

