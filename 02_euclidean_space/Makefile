lecture.html: lecture.ipynb
	jupyter-nbconvert lecture.ipynb --config ExecutePreprocessor.allow_errors=True --inplace 
	jupyter-nbconvert lecture.ipynb --to html

clean:
	jupyter-nbconvert lecture.ipynb --clear-output
