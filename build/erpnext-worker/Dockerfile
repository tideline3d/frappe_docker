ARG GIT_BRANCH=develop
FROM frappe/frappe-worker:${GIT_BRANCH}

ARG GIT_BRANCH
RUN install_app erpnext https://github.com/tideline3d/erpnext ${GIT_BRANCH}
