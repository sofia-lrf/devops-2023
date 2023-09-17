# 作业构建镜像体积尽可能小

# 使用alpine构建，可以达到镜像体积小的效果，生产环境不建议使用（换slim更稳定）
# scratch 空镜像可以使镜像体积尽量小，但是不方便运维或调试

# 使用buildkit构建效率高

# 构建并运行验证
# docker build -t go:test1 . -f Dockerfile-2
# docker run go:test1

