git filter-branch --env-filter '
if [ "$GIT_AUTHOR_NAME" = "hasan-py" ]; then \    
export GIT_AUTHOR_NAME="VietHoang24" GIT_AUTHOR_EMAIL="vietprock@gmail.com"; \
fi
'